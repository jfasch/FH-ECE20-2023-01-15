ADD_EXECUTABLE(
  cxx-exercises-stl--suite

  initial-failure.cpp

  # test-vector-append.cpp
  # test-vector-join.cpp
  # test-map-insert.cpp
  # test-map-insert_check_duplicate.cpp
  # test-map-insert_remove_by_key.cpp
  # test-map-find.cpp
  # test-algo-copy_into_vector.cpp
  # test-algo-find_in_vector.cpp
  # test-algo-sort-in-place.cpp
  # test-algo-sorted.cpp
  # test-filter-odd.cpp
  # test-filter-greater-10.cpp
)

TARGET_LINK_LIBRARIES(
  cxx-exercises-stl--suite

  cxx-exercises-stl-code
  gtest_main 
)
