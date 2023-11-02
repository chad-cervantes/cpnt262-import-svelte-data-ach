<h1>My name is Chad</h1>
<p>I am new to the world of web development</p>

<h1>This is a gallery page</h1>

<script>
  let dailyContent = 'Course Content';
  const description = 'This course is about web development';

  import Card from '../../lib/components/Card.svelte';
  const cardObj = {
    title: 'Alex',
    description:'23 years old',
    position: 'striker',
  };
</script>

<h2>SAIT Svelte {dailyContent}</h2>
<p>{description}</p>

<Card {...cardObj} />
<Card title="Xavier" description="21 years old" position="attacking midfielder"/>
<Card  title="Johnny" description="22 years old" position="left back"/>