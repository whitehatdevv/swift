target_sources(swiftSILOptimizer PRIVATE
  AccessEnforcementSelection.cpp
  AccessMarkerElimination.cpp
  AddressLowering.cpp
  CapturePromotion.cpp
  ClosureLifetimeFixup.cpp
  ConstantPropagation.cpp
  DefiniteInitialization.cpp
  DIMemoryUseCollector.cpp
  DataflowDiagnostics.cpp
  DiagnoseInfiniteRecursion.cpp
  DiagnoseInvalidEscapingCaptures.cpp
  DiagnoseLifetimeIssues.cpp
  DiagnoseStaticExclusivity.cpp
  DiagnoseUnreachable.cpp
  Differentiation.cpp
  IRGenPrepare.cpp
  LexicalLifetimeEliminator.cpp
  LowerHopToActor.cpp
  MandatoryInlining.cpp
  MoveOnlyChecker.cpp
  MoveKillsCopyableValuesChecker.cpp
  NestedSemanticFunctionCheck.cpp
  OptimizeHopToExecutor.cpp
  PerformanceDiagnostics.cpp
  PredictableMemOpt.cpp
  PMOMemoryUseCollector.cpp
  RawSILInstLowering.cpp
  SILGenCleanup.cpp
  YieldOnceCheck.cpp
  MandatoryCombine.cpp
  OSLogOptimization.cpp
  OwnershipModelEliminator.cpp)
