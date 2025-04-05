<p align="center">
  <img src="https://github.com/YoussefHasna0ui/YoussefHasna0ui/blob/main/profilethumb.png" />
</p>

```js
import { SoftwareDeveloper } from '@YoussefHasna0ui/Legend';

class Bio extends SoftwareDeveloper {
  name     = 'Youssef Hasnaoui';
  title    = 'Medical Student';
  location = 'Munich, Germany';
  bio      = 'Passionate medical student with a love for building impactful software solutions and a focus on full-stack development.';
  github   = 'https://github.com/YoussefHasna0ui';

  // Function to return email link for hiring inquiries
  hire() {
    return 'mailto:hasnaouiyoussef050@gmail.com?subject=Hiring Inquiry';
  }
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'Rust', 'Python', 'Golang', 'Java'];
  frameworks = [
    'React', 
    'Next.js', 
    'React Native', 
    'Vue', 
    'SvelteKit', 
    'Spring', 
    'Express.js', 
    'NestJS', 
    'Axum',
    'Gin',

  ];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL', 'Chroma', 'Weaviate'];
  tools      = ['Docker', 'Kubernetes', 'Git', 'Jenkins'];
  testingTools  = ['Jest', 'Mocha', 'Cypress', 'Selenium', 'Pytest'];
  methodologies = ['Scrum', 'DevOps'];
}
