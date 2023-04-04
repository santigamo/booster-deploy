# Docket action "fesbal-backend deploy"

This actions deploys your branch to the server.

## Inputs

### `access-key`

**Required** The accoybt secret access key to the server.

### `secret-key`

**Requires**  The AWS account secret key to the server.

### `region``

**Required** The AWS default region of the server.

### `boost-env``

**Required** The environment to deploy to.

## Output

TBD

## Example usage

``` YML
uses: actions/fesbal-backend@v1
with:
  access-key: ${{ secrets.AWS_ACCESS_KEY_ID }}
  secret-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
  region: ${{ secrets.AWS_DEFAULT_REGION }}
  boost-env: ${{ secrets.BOOST_ENV }}
```
