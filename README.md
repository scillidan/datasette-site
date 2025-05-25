The data here is not updated regularly. From

- csv:
	- [resource.csv](https://gist.github.com/scillidan/bbfc6b3c124316f67c3ab6a411bd3ad0)
- database:
	- [resource](https://www.dolthub.com/repositories/scillidan/resource)
	- [asset](https://www.dolthub.com/repositories/scillidan/asset)
	- [reference](https://www.dolthub.com/repositories/scillidan/reference)

Need to do:

- Get last update date base on url
	- Add checking rules
	- Get the last commit date from github_url
	- Get the last release date from github_url
- Clear `tag` column
	- Generate `readme_url` from `url`. Add checking action
	- Generate tags in `tag` column from content that from `readme_url`
- Clear `mark` column
	- Do something liked: analyze the `Package Control. sublime-settings` file to mark used packages with Sublime Text
- Move tables to one
	- Add a new `group` column
- Automatic sorting with multiple column
- Regularly download and generate database files from dolt
- Search in multiple column