```js
const styles = ['Primary', 'Danger', 'Warning', 'Success', 'Info', 'Default'];

styles.map((style, i) => {
  return (
    <Alert bsStyle={style.toLowerCase()} key={`button-${style}-${i}`}>
      <i className="fa fa-exclamation-triangle fa-fw fa-lg" />{' '}
      <strong>{style}</strong> Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </Alert>
  )
})
```
