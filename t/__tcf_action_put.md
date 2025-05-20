# Function: <code>__tcf_action_put</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819021e0)
Location: net/sched/act_api.c:101
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff819021e0-ffffffff8190224c: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81963330)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81963330-ffffffff8196339e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81999eb0)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81999eb0-ffffffff81999f1e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72c80)
Location: net/sched/act_api.c:125
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a72c80-ffffffff81a72cee: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b840)
Location: net/sched/act_api.c:141
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a7b840-ffffffff81a7b8ae: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a64550)
Location: net/sched/act_api.c:141
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_delete
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81a64550-ffffffff81a645be: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1d960)
Location: net/sched/act_api.c:141
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81b1d960-ffffffff81b1d9ce: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca5680)
Location: net/sched/act_api.c:379
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81ca5680-ffffffff81ca56fd: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e62190)
Location: net/sched/act_api.c:380
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81e62190-ffffffff81e6220d: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebdae0)
Location: net/sched/act_api.c:373
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81ebdae0-ffffffff81ebdb5d: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80bd0)
Location: net/sched/act_api.c:373
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_release
```
**Symbols:**

```
ffffffff81f80bd0-ffffffff81f80c4d: __tcf_action_put (STB_LOCAL)
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
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c472f8)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffff800010c472f8-ffff800010c473f4: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d5820c)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
c0d5820c-c0d582b8: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d43940)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
c000000000d43940-c000000000d43a30: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b494c)
Location: net/sched/act_api.c:125
Inline: False
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffe0007b494c-ffffffe0007b49dc: __tcf_action_put (STB_LOCAL)
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
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81939d20)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81939d20-ffffffff81939d8e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f3820)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff818f3820-ffffffff818f388e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198aeb0)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff8198aeb0-ffffffff8198af1e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __tcf_action_put(struct tc_action *p, bool bind);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ad710)
Location: net/sched/act_api.c:125
Inline: True
Direct callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_put_many
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff819ad710-ffffffff819ad77e: __tcf_action_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
