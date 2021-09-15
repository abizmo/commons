# useFetch

Demo:

```
  const url = 'http://site/endpoint'
  const { data, error, loading } = useFetch(url)
  loading && return <p>loading<p>
  data.map(...)
```