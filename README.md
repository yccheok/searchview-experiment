Previously, in `SherlockActionBar`, we are using `AutoCompleteTextView` in an `ActionBar` as an action view. This is because `SearchView` is not being supported in API <11.

In `AppCompat`, we need to figure out how we can achieve similar functionality, by using `android.support.v7.widget.SearchView`.

Problem faced in http://stackoverflow.com/q/30272114/72437 motivates us to migrate from `AutoCompleteTextView` to `android.support.v7.widget.SearchView`.
