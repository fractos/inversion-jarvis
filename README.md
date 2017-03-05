# inversion-jarvis

This is a service container design environment for Inversion.

It integrates with the [Inversion.Naiad](https://github.com/guy-murphy/inversion-dev/blob/master/Inversion.Naiad) service container to create working pipeline and storage configurations for Inversion-based applications.

- pipelines
- message names
- blocks of behaviour associated with particular messages
- configuration of criteria
- possible angle to use introspection of behaviour classes so they can advertise emitted messages, stores
- storage configuration including overrides
- prevent orphaned behaviours in service container
- typo detection / mitigation
- reading existing pipeline into design environment
- visualisation of pipeline and message branching
- IfElseBehaviour support
- BlockBehaviour support
- ParameterisedSequenceBehaviour support
- DispatchBehaviour support
- can those behaviour types be generalised? possible to have them share a base class that jarvis can recognise?
- PrototypedBehaviour support
- PrototypedWebBehaviour support
- PrototypedConcomitantBehaviour support
- PrototypedConcomitantWebBehaviour support
- Eval support
- store name override support in prototypes
- LoopBehaviour support

* TODO get Inversion into private AppVeyor account so can read from private NuGet repository in lieu of Guy's action.
