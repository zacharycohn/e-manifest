# The e-Manifest App for EPA

Visit [18F Consulting](https://pages.18f.gov/consulting/projects/epa/e-manifest/) for details about this project.

This is a Ruby/Sinatra app, with a Jekyll static site in the `_static` directory. The Jekyll site will be generated in the `public/` directory, which Sinatra routes to automatically.

Don't edit the `public/` folder directly! Jekyll will overwrite everything when building the site.

[View the live application »](https://e-manifest.18f.gov)

## Running Locally

1. Install Ruby
2. Run `bundle install` to grab the required gems.
3. Run `rake serve`. This will build the Jekyll site and start the Sinatra server.
4. Go to `localhost:9292` and enjoy!

## Rake Tasks

- To build the static site, run `rake build`.
- To build and serve the app, run `rake serve`.
- To deploy to 18F's cloud, run `rake deploy`.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
