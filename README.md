# NAME

Getopt::Constraint::Mouse - It's new $module

# SYNOPSIS

    #!perl
    use Getopt::Constraint::Mouse;

    my $options = Getopt::Constraint::Mouse->get_options(
        foo => 'Str',
        bar => { isa => 'Int', optional => 1 },
        baz => { isa => 'Str', default => 'Baz' }
    );

    my $foo = $options->{foo};
    my $bar = $options->{bar};
    my $baz = $options->{baz};

# DESCRIPTION

Getopt::Constraint::Mouse is ...

# LICENSE

Copyright (C) Hiroki Honda.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

Hiroki Honda <cside.story@gmail.com>
