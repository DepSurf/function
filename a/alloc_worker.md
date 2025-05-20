# Function: <code>alloc_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810985f0)
Location: kernel/workqueue.c:1610
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810985f0-ffffffff8109863e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b260)
Location: kernel/workqueue.c:1666
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff8109b260-ffffffff8109b2ae: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0060)
Location: kernel/workqueue.c:1668
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810a0060-ffffffff810a00ae: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ddf0)
Location: kernel/workqueue.c:1667
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff8109ddf0-ffffffff8109de3e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4570)
Location: kernel/workqueue.c:1668
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810a4570-ffffffff810a45be: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aaa80)
Location: kernel/workqueue.c:1700
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810aaa80-ffffffff810aaace: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b2f50)
Location: kernel/workqueue.c:1720
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810b2f50-ffffffff810b2f9e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8b40)
Location: kernel/workqueue.c:1816
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810b8b40-ffffffff810b8b8e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf060)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810bf060-ffffffff810bf0ae: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c87ce)
Location: kernel/workqueue.c:1816
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c392e)
Location: kernel/workqueue.c:1822
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c39c0)
Location: kernel/workqueue.c:1823
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810c39c0-ffffffff810c3a0e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d6560)
Location: kernel/workqueue.c:1853
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810d6560-ffffffff810d65ae: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810efee0)
Location: kernel/workqueue.c:1836
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810efee0-ffffffff810eff3a: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81111880)
Location: kernel/workqueue.c:1836
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff81111880-ffffffff811118da: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111dc30)
Location: kernel/workqueue.c:2038
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff8111dc30-ffffffff8111dc8a: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81127830)
Location: kernel/workqueue.c:2070
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff81127830-ffffffff811278b9: alloc_worker (STB_LOCAL)
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
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011bc80)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffff80001011bc80-ffff80001011bce8: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c03713c0)
Location: kernel/workqueue.c:1819
Inline: True
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
c03713c0-c0371420: alloc_worker.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000165ca0)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
c000000000165ca0-c000000000165d1c: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6a4e)
Location: kernel/workqueue.c:1819
Inline: True
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffe0000d6a4e-ffffffe0000d6a9c: alloc_worker.isra.0 (STB_LOCAL)
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
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b93d0)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810b93d0-ffffffff810b941e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7d10)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810a7d10-ffffffff810a7d5e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8930)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810b8930-ffffffff810b897e: alloc_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct worker *alloc_worker(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0dc0)
Location: kernel/workqueue.c:1819
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810c0dc0-ffffffff810c0e0e: alloc_worker (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
