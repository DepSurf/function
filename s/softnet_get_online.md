# Function: <code>softnet_get_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff817376c5)
Location: net/core/net-procfs.c:118
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_start
  - net/core/net-procfs.c:softnet_seq_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff817a39f3)
Location: net/core/net-procfs.c:118
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff817d2483)
Location: net/core/net-procfs.c:118
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff817f1873)
Location: net/core/net-procfs.c:118
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff8186ce4f)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff818be0cf)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff818e54af)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff819353e0)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff819353e0-ffffffff81935432: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff819681a0)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff819681a0-ffffffff819681f2: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81a3b8d0)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81a3b8d0-ffffffff81a3b922: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81a3dfd0)
Location: net/core/net-procfs.c:125
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81a3dfd0-ffffffff81a3e022: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81a250a0)
Location: net/core/net-procfs.c:122
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81a250a0-ffffffff81a250f2: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81ad9b40)
Location: net/core/net-procfs.c:122
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81ad9b40-ffffffff81ad9bbc: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81c5acf0)
Location: net/core/net-procfs.c:124
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81c5acf0-ffffffff81c5ad80: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81e10f00)
Location: net/core/net-procfs.c:124
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81e10f00-ffffffff81e10f90: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81e84810)
Location: net/core/net-procfs.c:128
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81e84810-ffffffff81e848a0: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81f467c0)
Location: net/core/net-procfs.c:128
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81f467c0-ffffffff81f46850: softnet_get_online (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffff800010c0d7a8)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (c0d25870)
Location: net/core/net-procfs.c:119
Inline: False
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
c0d25870-c0d2591c: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (c000000000cf8e74)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffe00078a44e)
Location: net/core/net-procfs.c:119
Inline: True
Inline callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff81908170)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff81908170-ffffffff819081c2: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff818c1f80)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff818c1f80-ffffffff818c1fd2: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff819591a0)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff819591a0-ffffffff819591f2: softnet_get_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct softnet_data *softnet_get_online(loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-procfs.c (ffffffff8197b310)
Location: net/core/net-procfs.c:119
Inline: True
Direct callers:
  - net/core/net-procfs.c:softnet_seq_next
  - net/core/net-procfs.c:softnet_seq_start
```
**Symbols:**

```
ffffffff8197b310-ffffffff8197b362: softnet_get_online (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
