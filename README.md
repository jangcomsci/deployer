# deployer

<?xml version="1.0" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<link rev="made" href="mailto:" />
</head>

<body>



<ul id="index">
  <li><a href="#NAME">NAME</a></li>
  <li><a href="#SYNOPSIS">SYNOPSIS</a></li>
  <li><a href="#DESCRIPTION">DESCRIPTION</a></li>
  <li><a href="#OPTIONS">OPTIONS</a></li>
  <li><a href="#EXAMPLES">EXAMPLES</a></li>
  <li><a href="#REQUIREMENTS">REQUIREMENTS</a></li>
  <li><a href="#SEE-ALSO">SEE ALSO</a></li>
  <li><a href="#AUTHOR">AUTHOR</a></li>
  <li><a href="#COPYRIGHT">COPYRIGHT</a></li>
  <li><a href="#LICENSE">LICENSE</a></li>
</ul>

<h1 id="NAME">NAME</h1>

<p>deployer - File deployment assistant</p>

<h1 id="SYNOPSIS">SYNOPSIS</h1>

<pre><code>    perl deployer.pl [-deploy_path=path]
                     [-all] [old_file=new_file ...]
                     [-nofm] [-nopause]</code></pre>

<h1 id="DESCRIPTION">DESCRIPTION</h1>

<p>Copy-paste files to a designated path.</p>

<h1 id="OPTIONS">OPTIONS</h1>

<pre><code>    -deploy_path=path (short from: -path)
        The path to which designated files will be deployed.

    -all (short form: -a)
        All files in the current working directory will be deployed.

    old_file=new_file ...
        A pair of a filename and its to-be-deployed filename.
        old_file will be used as new_file if new_file is omitted.
        Multiple pairs should be delimited by the space character.
        Accordingly, no space characters are allowed around the equals sign (=).

    -nofm
        The front matter will not be displayed at the beginning of the program.

    -nopause
        The shell will not be paused at the end of the program.
        Use it for a batch run.</code></pre>

<h1 id="EXAMPLES">EXAMPLES</h1>

<pre><code>    perl deployer.pl -path=../to_boss/ whatnot.pptx=report.pptx
    perl deployer.pl -path=./shibas/ mame_shiba.png
    perl deployer.pl -path=./inus/ -a</code></pre>

<h1 id="REQUIREMENTS">REQUIREMENTS</h1>

<p>Perl 5</p>

<h1 id="SEE-ALSO">SEE ALSO</h1>

<p><a href="https://github.com/jangcom/deployer">deployer on GitHub</a></p>

<h1 id="AUTHOR">AUTHOR</h1>

<p>Jaewoong Jang &lt;jangj@korea.ac.kr&gt;</p>

<h1 id="COPYRIGHT">COPYRIGHT</h1>

<p>Copyright (c) 2017-2019 Jaewoong Jang</p>

<h1 id="LICENSE">LICENSE</h1>

<p>This software is available under the MIT license; the license information is found in &#39;LICENSE&#39;.</p>


</body>

</html>
