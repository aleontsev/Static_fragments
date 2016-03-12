# Descriptive example of static fragments lifecycle.

Callback Sequence: 

Fragment1 onAttach 

Fragment1 onCreate 

Fragment1 onCreateView

Fragment2 onAttach

Fragment2 onCreate

Fragment2 onCreateView

MainActivity onCreate

Fragment1 onActivityCreated

Fragment2 onActivityCreated

MainActivity onStart

Fragment1 onStart

Fragment2 onStart

MainActivity onResume

Fragment1 onResume

Fragment2 onResume
