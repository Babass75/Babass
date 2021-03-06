## Whatβs changed

So, the first release had bugs and needed improvements π¬ 
But this release fixes a lot of them! Thanks for the feedback and reports π 

Subnet & Exit node routing has been fixed, additionally, the add-on will now only expose subnets that can be routed on your system.

## π Bug fixes

- π Use netfilter for iptables @frenck (#17)

## π Enhancements

- π Update sidebar icon from Docker -> VPN @frenck (#11)
- π Skip local link addresses in routes advertisement @frenck (#18)
- π Skip address family from route advertisement if it has forwarding disabled @frenck (#19)

## π Documentation

- π Adjust i386 badge, as that is a supported architecture @frenck (#7)

## β¬οΈ Dependency updates

- Bump docker/build-push-action from 2.6.1 to 2.7.0 @dependabot (#15)
- β¬οΈ Upgrades Tailscale to 1.14.0 @frenck (#16)
