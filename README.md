# Personal Website

The deploy is done with [Frozen-Flask](https://pythonhosted.org/Frozen-Flask/) and [Netlify](https://www.netlify.com/).

## Development

If you install new packages, remember to update `requirements.txt`:

```sh
pip freeze > requirements.txt
```

## Deployment

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-dark.svg"/>
</a>

### Netlify settings

* Build command: `python freeze.py`
* Publish directory: `build`
