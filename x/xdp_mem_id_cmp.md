# Function: <code>xdp_mem_id_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818ba540)
Location: net/core/xdp.c:52
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff818ba540-ffffffff818ba55a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e13c0)
Location: net/core/xdp.c:55
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff818e13c0-ffffffff818e13da: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8192fba0)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
**Symbols:**

```
ffffffff8192fba0-ffffffff8192fbba: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81961e10)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81961e10-ffffffff81961e2a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a3641a)
Location: net/core/xdp.c:48
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81a35590-ffffffff81a355aa: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37920)
Location: net/core/xdp.c:48
Inline: True
```
**Symbols:**

```
ffffffff81a37920-ffffffff81a3793a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ea80)
Location: net/core/xdp.c:48
Inline: True
```
**Symbols:**

```
ffffffff81a1ea80-ffffffff81a1ea9a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad2b20)
Location: net/core/xdp.c:48
Inline: True
```
**Symbols:**

```
ffffffff81ad2b20-ffffffff81ad2b3a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51140)
Location: net/core/xdp.c:48
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
**Symbols:**

```
ffffffff81c505f0-ffffffff81c50614: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e059f0)
Location: net/core/xdp.c:48
Inline: True
```
**Symbols:**

```
ffffffff81e059f0-ffffffff81e05a14: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e78af3)
Location: net/core/xdp.c:50
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
**Symbols:**

```
ffffffff81e780d0-ffffffff81e780f4: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f389c3)
Location: net/core/xdp.c:50
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
**Symbols:**

```
ffffffff81f38090-ffffffff81f380b4: xdp_mem_id_cmp (STB_LOCAL)
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
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c05c18)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffff800010c05c18-ffff800010c05c54: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1ec68)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
c0d1ec68-c0d1ec94: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000ceff00)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
c000000000ceff00-c000000000ceff28: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784386)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffe000784386-ffffffe0007843ba: xdp_mem_id_cmp (STB_LOCAL)
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
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81901de0)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81901de0-ffffffff81901dfa: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bbc10)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff818bbc10-ffffffff818bbc2a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81952e10)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81952e10-ffffffff81952e2a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdp_mem_id_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81974900)
Location: net/core/xdp.c:46
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81974900-ffffffff8197491a: xdp_mem_id_cmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
