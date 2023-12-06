<script>
  import { Node, Svelvet, Minimap, Controls } from 'svelvet';
</script>

<Svelvet id="my-canvas" width="{500}" height="{500}" TD controls>
  <Node />
  <Node id="alpha" bgColor="red" label="Default Node" inputs="{3}" />
</Svelvet>
