# Orbit

Orbit is an A-Frame component that allows an entity to orbit around a fixed point.

## Installation

Include the component file in the head of your HTML document:

```html
<script type="text/javascript" src="orbit.js"></script>
```

## Usage

```html
<a-entity
  orbit="
  	radius: 10; 
  	updateDelta: 25;
  	speed: 1;
  "
>
</a-entity>
```

## Parameters

| Parameter          | Default | Description |
|--------------------|---------|-------------|
| **radius**         | 10      | The radius of the circle that the orbit encompasses|
| **updateDelta**    | 0       | The total time between each point calculation (in milliseconds)|
| **speed**          | 1       | The speed of the orbit|

## Example

![](orbit.gif)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
