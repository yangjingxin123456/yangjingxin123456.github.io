一个学术网站的 Github Pages 模板。 这是由 [Stuart Geiger](https://github.com/staeiou) 从 [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) 分叉（然后分离），这是 ©2016 Michael Rose 在 MIT 许可下发布。参见 LICENSE.md。

我想我已经顺利运行并修复了一些主要错误，但是如果您想改进通用模板/主题，请随时提交问题或提出拉取请求。

### 注意：如果您正在使用这个 repo 并且现在收到有关安全漏洞的通知，请删除 Gemfile.lock 文件。

# 介绍

1. 如果您没有，请注册一个 GitHub 帐户并确认您的电子邮件（必需！）
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by 单击右上角的“fork”按钮. 
1. 转到存储库的设置（以“Code”开头的选项卡中最右侧的项目应位于“unwatch”下方）. Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
