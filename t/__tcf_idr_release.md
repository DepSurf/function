# Function: <code>__tcf_idr_release</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81881dc0)
Location: net/sched/act_api.c:87
Inline: True
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81881dc0-ffffffff81881e9e: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d50b0)
Location: net/sched/act_api.c:87
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff818d50b0-ffffffff818d51e4: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8190269e)
Location: net/sched/act_api.c:121
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff819022b0-ffffffff819022ea: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819638f6)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff81963400-ffffffff8196343a: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199a476)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff81999f80-ffffffff81999fba: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a73a7c)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a72cf0-ffffffff81a72d2a: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7c67c)
Location: net/sched/act_api.c:161
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a7b8b0-ffffffff81a7b8ea: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a6530c)
Location: net/sched/act_api.c:161
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1e5cc)
Location: net/sched/act_api.c:161
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca5fdc)
Location: net/sched/act_api.c:399
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e6247c)
Location: net/sched/act_api.c:400
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebe50c)
Location: net/sched/act_api.c:393
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f8165c)
Location: net/sched/act_api.c:393
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c4754c)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffff800010c473f8-ffff800010c47464: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d583e4)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
c0d582b8-c0d58304: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d44a1c)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
c000000000d43ad0-c000000000d43b48: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b56c8)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffe0007b4f8c-ffffffe0007b4fde: __tcf_idr_release (STB_GLOBAL)
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
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193a2e6)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff81939df0-ffffffff81939e2a: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3de6)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff818f38f0-ffffffff818f392a: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198b476)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff8198af80-ffffffff8198afba: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __tcf_idr_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819adce6)
Location: net/sched/act_api.c:145
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff819ad7e0-ffffffff819ad81a: __tcf_idr_release (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
