# emotion-meyer-reset

[Eric Meyer's reset](https://meyerweb.com/eric/tools/css/reset/) for [Emotion](https://emotion.sh/) CSS-in-JS library.

## Usage

	npm install --save emotion-meyer-reset
	
### Javascript

```javascript
	import {Global,css} from "@emotion/core";
	import reset from "emotion-meyer-reset";
	
	// …
	
	<Global
	  styles={css`
	    ${reset}
	    html,
	    body {
	      background: white;
	      min-height: 100%;
	      font-family: Helvetica, Arial, sans-serif;
	      // …
	    }
	  `}
	/>
```

## License

The [MIT License](./LICENSE)