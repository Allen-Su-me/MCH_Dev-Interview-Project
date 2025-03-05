<template>
  <div class="project-card">
    <div class="project-image">
      <img :src="imageUrl" :alt="title" @error="onImageError">
    </div>
    <div class="project-content">
      <h3 class="project-title">{{ title }}</h3>
      <p class="project-description">{{ description }}</p>
      <div class="tech-stack">
        <span v-for="(tech, index) in technologies" :key="index" class="tech-tag">
          {{ tech }}
        </span>
      </div>
      <a :href="projectUrl" target="_blank" class="view-project">
        查看專案 <i class="fas fa-external-link-alt"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProjectCard',
  props: {
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    },
    technologies: {
      type: Array,
      default: () => []
    },
    imageUrl: {
      type: String,
      default: ''
    },
    projectUrl: {
      type: String,
      required: true
    }
  },
  methods: {
    onImageError(e) {
      e.target.src = '/images/placeholder.jpg'; // Fallback image
    }
  }
}
</script>

<style scoped>
.project-card {
  background-color: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
  transition: all 0.3s ease;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.12);
}

.project-image {
  height: auto;
  padding: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.project-image img {
  width: 100%;
  height: 200px;
  object-fit: contain;
  transition: transform 0.5s ease;
}

.project-card:hover .project-image img {
  transform: scale(1.05);
}

.project-content {
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  flex: 1;
}

.project-title {
  font-size: 1.3rem;
  font-weight: 600;
  margin: 0 0 0.8rem 0;
  color: #1a1a1a;
}

.project-description {
  font-size: 1rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 1.5rem;
  flex: 1;
}

.tech-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
}

.tech-tag {
  background-color: #f0f0f0;
  color: #555;
  padding: 0.3rem 0.8rem;
  border-radius: 30px;
  font-size: 0.85rem;
  transition: all 0.3s ease;
}

.tech-tag:hover {
  background-color: #e0e0e0;
}

.view-project {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: #656d73;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  margin-top: auto;
  transition: all 0.3s ease;
}

.view-project:hover {
  color: #36383a;
}

.view-project i {
  font-size: 0.8rem;
}
</style>
