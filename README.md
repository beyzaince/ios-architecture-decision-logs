# Architectural Decision Records (ADR)

This log lists the architectural decisions for Trendyol iOS Project.

<!-- adrlog -- Regenerate the content by using "adr-log -i". You can install it via "npm install -g adr-log" -->

- [ADR-0000](adr/0000-use-xctest-for-unit-test.md) - Using XCTest for unit test instead of Quick/Nimble
- [ADR-0001](adr/0001-every-view-which-has-logic-inside-should(must)-have-presenter.md) - Every view which has logic inside should(must) have presenter
- [ADR-0002](adr/0002-use-view-model-on-necessary-place.md) - If it is necessary to manipulate the DTO models that the UI will use, the ViewModel class needs to be created
- [ADR-0003](adr/0003-dont-use-chain-delegate.md) - Don't Use Chain Delegate
- [ADR-0004](adr/0004-use-mock-generator.md) - Use Mock Generator
- [ADR-0005](adr/0005-inject-ab-config-global-values-toPresenter.md) - Inject AB, Config, Global values to presenters
- [ADR-0006](adr/0006-inject-parameters-asArguments-toPresenter.md) - Inject parameters as arguments to presenters
- [ADR-0007](adr/0007-presenter-casting-as-delegate.md) - Define any delegate on presenter interface to pass
- [ADR-0008](adr/0008-layering-modular-ios-application.md) - Layering Modular iOS Application
- [ADR-0009](adr/0009-layering-modular-ios-application-approach.md) - Layering Modular iOS Application Approach
- [ADR-0010](adr/0010-use-localizable-kit-for-localization.md) - Using Localizable Kit for Localization
- [ADR-0011](adr/0011-name-test-methods.md) - Naming Test Methods
- [ADR-0012](adr/0012-use-networkManager-for-network-requests.md) - Use networkManager for network requests
- [ADR-0013](adr/0013-unit-tests-required.md) - Unit Tests Required
- [ADR-0014](adr/0014-use-CoreTracker-for-trackingEvents.md) - Use coreTracker for tracking events

<!-- adrlogstop -->

For new ADRs, please use [TrendyolAdrTemplate.md](TrendyolAdrTemplate.md) as basis.
