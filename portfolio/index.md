---
works_index: true
hero_text: "<strong>We're Acme</strong>, we work for brands. But most importantly,
  we work for fun."
title: Hero
test_content: Halo

---
<Hero :text="$page.frontmatter.hero_text" />

<Hero :text="$page.frontmatter.test_content" />

<WorksList />