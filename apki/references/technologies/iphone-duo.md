# iPhone Duo

Use these Apple primary sources when adapting an app to iPhone Duo’s outer and inner displays, folding poses, resizable layouts, vertical system bars, multiple scenes, hinge interactions, or camera behavior.

## Primary sources

- [Get ready for iPhone Duo](https://developer.apple.com/iphone-duo/) — launch hub for videos, developer activities, Xcode, documentation, and design resources
- [Preparing your app for iPhone Duo](https://developer.apple.com/documentation/technologyoverviews/preparing-your-app-for-iphone-duo) — implementation overview covering resizing, vertical bars, arrangement views, reserved regions, cameras, and testing across displays and poses
- [Designing for iPhone Duo](https://developer.apple.com/design/human-interface-guidelines/designing-for-iphone-duo) — HIG guidance covering anatomy, poses, dynamic layouts, reserved regions, split and arrangement views, and vertical controls
- Verified: `2026-10-22`

The launch hub currently lists **six Tech Talks** and three Group Lab recordings. “Get ready for iPhone Duo” is the hub’s title, not a seventh Tech Talk. The Apple video catalogue includes four recorded Group Labs.

## Apple developer videos

- [Design for iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111466/) — design principles, display configurations, size classes, control placement, sheets, and fold avoidance
- [Prepare your app for iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111461/) — SDK adoption, Xcode simulation, flexible layouts, size classes, safe areas, and Split View testing
- [Raise the bar with iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111462/) — adaptive navigation, toolbars, tab bars, vertical representations, and overflow
- [Strike a pose with adaptive layouts on iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111463/) — reserved regions, displacement patterns, and arrangement views in SwiftUI and UIKit
- [Leverage multiple displays and scenes on iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111464/) — hinge updates, multitasking, multiple scenes, and scene accessories across displays
- [Build a great camera experience for iPhone Duo](https://developer.apple.com/videos/play/tech-talks/111465/) — inner and outer cameras, Virtual Front Camera, direction changes, previews, and rotation

Open each video page for its current chapter summaries, code examples, related videos, and downloads. The complete Tech Talks catalogue, including Apple’s full summaries and metadata for these sessions, is in [Tech Talks](../videos/other/tech-talks.md).

## Group Labs

- [iPhone Duo Group Lab — recording 288](https://developer.apple.com/videos/play/meet-with-apple/288/) — layouts across displays and poses, the hinge, Split View multitasking, and camera experiences
- [iPhone Duo Group Lab — Day 3, recording 287](https://developer.apple.com/videos/play/meet-with-apple/287/) — layouts across displays and poses, the hinge, Split View multitasking, and camera experiences
- [iPhone Duo Group Lab — recording 286](https://developer.apple.com/videos/play/meet-with-apple/286/) — layouts across displays and poses, the hinge, Split View multitasking, and camera experiences
- [iPhone Duo Group Lab — recording 285](https://developer.apple.com/videos/play/meet-with-apple/285/) — layouts across displays and poses, the hinge, Split View multitasking, and camera experiences

The complete collection metadata is in [Meet with Apple](../videos/other/meet-with-apple.md).

## Related WWDC sessions

- [Modernize your UIKit app](https://developer.apple.com/videos/play/wwdc2026/278/) — resizable UIKit layouts, updated tab and navigation bars, and current modernization APIs
- [Make your UIKit app more flexible](https://developer.apple.com/videos/play/wwdc2025/282/) — scenes, window resizing, multitasking, split views, inspectors, and adaptive layout APIs

## High-value API routes

- Adaptive composition: [ArrangementView](https://developer.apple.com/documentation/swiftui/arrangementview) and [UIArrangementViewController](https://developer.apple.com/documentation/uikit/uiarrangementviewcontroller)
- Fold and camera avoidance: [ReservedRegion](https://developer.apple.com/documentation/swiftui/reservedregion) and [UIView.ReservedRegion](https://developer.apple.com/documentation/uikit/uiview/reservedregion)
- Vertical bars: [toolbarVerticalEdge](https://developer.apple.com/documentation/swiftui/environmentvalues/toolbarverticaledge), [axisBehavior(_:)](https://developer.apple.com/documentation/swiftui/toolbarcontent/axisbehavior(_:)), [visibilityPriority(_:)](https://developer.apple.com/documentation/swiftui/toolbarcontent/visibilitypriority(_:)), and [ToolbarOverflowMenu](https://developer.apple.com/documentation/swiftui/toolbaroverflowmenu)
- Camera direction and dual-display capture: [Choosing a camera by the direction it faces](https://developer.apple.com/documentation/avkit/choosing-a-camera-by-the-direction-it-faces) and [Registering a camera capture accessory on iPhone Duo](https://developer.apple.com/documentation/avfoundation/registering-a-camera-capture-accessory-on-iphone-duo)

## Time-sensitive material

The launch hub’s Xcode beta, workshops, live Q&As, and design-resource availability are time-sensitive. Check the live hub before reporting dates or availability.
