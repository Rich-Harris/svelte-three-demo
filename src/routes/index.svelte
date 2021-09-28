<script>
	import * as THREE from 'three';
	import * as GL from 'svelte-three';
</script>

<GL.Canvas>
	<GL.Mesh geometry={new THREE.BoxGeometry()}/>
	<GL.PerspectiveCamera position={[2, 2, 5]}/>
</GL.Canvas>