# NAME

YAML::YAML2ADoc - Something like yaml2rst but for AsciiDoc and in Perl

# SYNOPSIS

    use YAML::YAML2ADoc;

    my $output_file = 'defaults.adoc';
    my @input_files = ('defaults.yaml');
    YAML::YAML2ADoc::run($output_file, \@input_files);

# DESCRIPTION

YAML::YAML2ADoc the module for `yaml2adoc`. Please refer to the script
file for further information.

# AUTHOR

Bertalan Zoltán Péter <bertalan.peter@bp99.eu>

# COPYRIGHT

Copyright 2022- Bertalan Zoltán Péter

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO
