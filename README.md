[<img src="http://threemammals.com/images/ocelot_logo.png">](http://threemammals.com/ocelot)

[![Build status](https://ci.appveyor.com/api/projects/status/8ry4ailt7rr5mbu7?svg=true)](https://ci.appveyor.com/project/TomPallister/ocelot-cache-cachemanager)
Windows (AppVeyor)
[![Build Status](https://travis-ci.org/ThreeMammals/Ocelot.Package.Archetype.svg?branch=master)](https://travis-ci.org/ThreeMammals/Ocelot.Package.Archetype) Linux & OSX (Travis)

[![Coverage Status](https://coveralls.io/repos/github/ThreeMammals/Ocelot.Package.Archetype/badge.svg?branch=develop)](https://coveralls.io/github/ThreeMammals/Ocelot.Package.Archetype?branch=develop)

# Ocelot

This package adds [Consul](https://www.consul.io/) support to Ocelot via the package [Consul](https://github.com/PlayFab/consuldotnet).

## How to install

Ocelot is designed to work with ASP.NET Core only and it targets `netstandard2.0`. This means it can be used anywhere `.NET Standard 2.0` is supported, including `.NET Core 2.1` and `.NET Framework 4.7.2` and up. [This](https://docs.microsoft.com/en-us/dotnet/standard/net-standard) documentation may prove helpful when working out if Ocelot would be suitable for you.

Install Ocelot and it's dependencies using NuGet. 

`Install-Package Ocelot.Package.Archetype`

Or via the .NET Core CLI:

`dotnet add package Ocelot.Package.Archetype`

All versions can be found [here](https://www.nuget.org/packages/Ocelot.Package.Archetype/)

## Documentation

Please click [here](http://ocelot.readthedocs.io/en/latest/features/servicediscovery.html) for the Ocleot serviec discovery documentation and [here](http://ocelot.readthedocs.io/en/latest/features/configuration.html#store-configuration-in-consul) for storing configuration in Consul. This includes lots of information and will be helpful if you want to understand the features Ocelot currently offers.

## Contributing

We love to receive contributions from the community so please keep them coming :) 

Pull requests, issues and commentary welcome!

Please complete the relevant template for issues and PRs. Sometimes it's worth getting in touch with us to discuss changes 
before doing any work incase this is something we are already doing or it might not make sense. We can also give
advice on the easiest way to do things :)

Finally we mark all existing issues as help wanted, small, medium and large effort. If you want to contribute for the first time I suggest looking at a help wanted & small effort issue :)

## Donate

If you think this project is worth supporting financially please make a contribution using the button below!

[![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://www.paypal.me/ThreeMammals/)


