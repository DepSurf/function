# Function: <code>put_unbound_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109aba0)
Location: kernel/workqueue.c:3142
Inline: False
Direct callers:
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8109aba0-ffffffff8109ad73: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e1a0)
Location: kernel/workqueue.c:3243
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff8109e1a0-ffffffff8109e37b: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2d00)
Location: kernel/workqueue.c:3269
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810a2d00-ffffffff810a2edb: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0030)
Location: kernel/workqueue.c:3267
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810a0030-ffffffff810a01de: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6d50)
Location: kernel/workqueue.c:3278
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810a6d50-ffffffff810a6f58: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810acc20)
Location: kernel/workqueue.c:3351
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810acc20-ffffffff810ace47: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b64a0)
Location: kernel/workqueue.c:3374
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810b64a0-ffffffff810b66c7: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3513
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810bc2b0-ffffffff810bc4df: put_unbound_pool (STB_LOCAL)
ffffffff810bf00b-ffffffff810bf044: put_unbound_pool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2570)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c27a9: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8a40)
Location: kernel/workqueue.c:3530
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff810c8a40-ffffffff810c8c63: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3ba0)
Location: kernel/workqueue.c:3536
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff810c3ba0-ffffffff810c3dc3: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c53c0)
Location: kernel/workqueue.c:3537
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff810c53c0-ffffffff810c55e0: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d7fb0)
Location: kernel/workqueue.c:3576
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff810d7fb0-ffffffff810d81bf: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ee880)
Location: kernel/workqueue.c:3559
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff810ee880-ffffffff810eea72: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110ff30)
Location: kernel/workqueue.c:3566
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff8110ff30-ffffffff81110122: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81120aa0)
Location: kernel/workqueue.c:3872
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff81120aa0-ffffffff81120d4c: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112a350)
Location: kernel/workqueue.c:3961
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_release_workfn
  - kernel/workqueue.c:get_unbound_pool
```
**Symbols:**

```
ffffffff8112a350-ffffffff8112a5fc: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011e438)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffff80001011e438-ffff80001011e6d4: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0370238)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
c0370238-c03704b8: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000169340)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
c000000000169340-c000000000169688: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7ca2)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffe0000d7ca2-ffffffe0000d7ed6: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc8e0)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810bc8e0-ffffffff810bcb19: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab140)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810ab140-ffffffff810ab36d: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bbe40)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810bbe40-ffffffff810bc079: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_unbound_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0e10)
Location: kernel/workqueue.c:3522
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:pwq_unbound_release_workfn
```
**Symbols:**

```
ffffffff810c0e10-ffffffff810c101e: put_unbound_pool (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
