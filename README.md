HTTP::Strip
================

Strip HTML markup from text.

        use HTML::Strip;
        my $html = q{<body>my <a href="http://">perl module</a></body>};
        my $clean = html_strip($html);
        # $clean: my perl module 

HTML::Strip removes HTML tags and comments from given text.

See embedded POD documentation for more information.
