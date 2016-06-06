Simple Youtube
========

A simple way to access the youtube search API


####Options####

```
{
key: String (required)
term: String (required)
number: Number (optional, defaults to 5)
}
```

####Example:####
Search for 'hello world' and return 15 results

```
import SimpleYT from 'simple-youtube'

SimpleYT({
  key: YOUR_API_KEY,
  term: 'hello world',
  number: 15,
  }, (videos) => {
  this.setState({videos})
})
```

