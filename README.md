# Star Rating Component Svelte

_A Simple on hover rating component for svelte._

## To use 🔧
If using Svelte:

```bash 
npm install svelte-stars-hover-rating
```

If using Sapper (install as a dev dependency):

```bash 
npm install -D svelte-stars-hover-rating"
```
  
And import it into your file:
```svelte
<script>
  import {Rating} from 'svelte-stars-hover-rating';
  let rate=null
</script>

<Rating bind:rating={rate} />
```

Props:

| Prop   | Type   | Default | Required | Description                                           |
| ------ | ------ | ------- | -------- | ----------------------------------------------------- |
| num    | Number | -       | No       | The number of stars. Default is 5                     |
| rating | Number | -       | No       | Passes back the rating value inputted by user         |
