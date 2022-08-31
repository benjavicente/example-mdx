---
title: Example Post
published: 2021-02-13
description: This is some description
---
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);
  return (
    <div>
      <h1>{count}</h1>
      <button onClick={() => setCount(count + 1)}>+</button>
    </div>
  )
}

# Wahoo

Here's a **neat** demo:

<Counter/>
