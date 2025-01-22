# React Native FlatList Rendering Issue

This repository demonstrates a common bug in React Native where a FlatList component fails to render data from an API call, even when the data state is correctly populated.  The issue is subtle and may be related to how the FlatList component handles updates to the data prop when the previous state was an empty array.