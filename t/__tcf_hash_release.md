# Function: <code>__tcf_hash_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __tcf_hash_release(struct tc_action *a, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747480)
Location: net/sched/act_api.c:56
Inline: True
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
```
**Symbols:**

```
ffffffff81747480-ffffffff8174756a: __tcf_hash_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __tcf_hash_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b4650)
Location: net/sched/act_api.c:53
Inline: True
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_hashinfo_destroy
```
**Symbols:**

```
ffffffff817b4650-ffffffff817b4737: __tcf_hash_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __tcf_hash_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3f00)
Location: net/sched/act_api.c:59
Inline: True
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_hashinfo_destroy
```
**Symbols:**

```
ffffffff817e3f00-ffffffff817e3fe3: __tcf_hash_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __tcf_hash_release(struct tc_action *p, bool bind, bool strict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818038d0)
Location: net/sched/act_api.c:86
Inline: True
Direct callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_hashinfo_destroy
```
**Symbols:**

```
ffffffff818038d0-ffffffff81803993: __tcf_hash_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tc_action *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tc_action *a</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
