# Swift Language and Concurrency Index

Use this as a fast path for a named Swift type or concurrency feature, then continue in the linked primary source. This is a selected entry point, not a replacement for the language guide or complete standard library.

- Apple reference: [Swift](https://developer.apple.com/documentation/swift)
- Official language guide: [The Swift Programming Language](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/)
- Component links last verified: `2026-07-17T17:29:00Z`

## Core language and standard library

- Scalar and absence: [Bool](https://developer.apple.com/documentation/swift/bool), [Int](https://developer.apple.com/documentation/swift/int), [Double](https://developer.apple.com/documentation/swift/double), [String](https://developer.apple.com/documentation/swift/string), [Optional](https://developer.apple.com/documentation/swift/optional), [Never](https://developer.apple.com/documentation/swift/never)
- Collections: [Array](https://developer.apple.com/documentation/swift/array), [Dictionary](https://developer.apple.com/documentation/swift/dictionary), [Set](https://developer.apple.com/documentation/swift/set)
- Results and errors: [Result](https://developer.apple.com/documentation/swift/result), [Error](https://developer.apple.com/documentation/swift/error)

## Swift Concurrency

- Concurrency overview: [Concurrency](https://developer.apple.com/documentation/swift/concurrency)
- Tasks: [Task](https://developer.apple.com/documentation/swift/task), [TaskGroup](https://developer.apple.com/documentation/swift/taskgroup), [TaskPriority](https://developer.apple.com/documentation/swift/taskpriority), [CancellationError](https://developer.apple.com/documentation/swift/cancellationerror)
- Isolation and transfer: [Actor](https://developer.apple.com/documentation/swift/actor), [MainActor](https://developer.apple.com/documentation/swift/mainactor), [GlobalActor](https://developer.apple.com/documentation/swift/globalactor), [Sendable](https://developer.apple.com/documentation/swift/sendable)
- Async sequences and bridging: [AsyncSequence](https://developer.apple.com/documentation/swift/asyncsequence), [AsyncStream](https://developer.apple.com/documentation/swift/asyncstream), [AsyncThrowingStream](https://developer.apple.com/documentation/swift/asyncthrowingstream), [CheckedContinuation](https://developer.apple.com/documentation/swift/checkedcontinuation)
- Migration and current language mode: [Adopting strict concurrency in Swift 6 apps](https://developer.apple.com/documentation/swift/adoptingswift6), [Swift updates](https://developer.apple.com/documentation/Updates/Swift)

## Focused Apple sessions

- [Embracing Swift concurrency (WWDC25)](https://developer.apple.com/videos/play/wwdc2025/268/) — current introduction to adopting asynchronous and concurrent work.
- [Code-along: Elevate an app with Swift concurrency (WWDC25)](https://developer.apple.com/videos/play/wwdc2025/270/) — practical data-race safety and structured-concurrency workflow.
- [Migrate your app to Swift 6 (WWDC24)](https://developer.apple.com/videos/play/wwdc2024/10169/) — incremental migration and isolation boundaries.
