# Function: <code>tcf_hash_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tcf_common *tcf_hash_lookup(u32 index, struct tcf_hashinfo *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81746c20)
Location: net/sched/act_api.c:179
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_hash_search
  - net/sched/act_api.c:tcf_hash_check
  - net/sched/act_api.c:tcf_hash_create
```
**Symbols:**

```
ffffffff81746c20-ffffffff81746c75: tcf_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tc_action *tcf_hash_lookup(u32 index, struct tcf_hashinfo *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b3ee0)
Location: net/sched/act_api.c:177
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_hash_check
  - net/sched/act_api.c:tcf_hash_search
  - net/sched/act_api.c:tcf_hash_new_index
```
**Symbols:**

```
ffffffff817b3ee0-ffffffff817b3f5b: tcf_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tc_action *tcf_hash_lookup(u32 index, struct tcf_hashinfo *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3760)
Location: net/sched/act_api.c:183
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_hash_check
  - net/sched/act_api.c:tcf_hash_search
  - net/sched/act_api.c:tcf_hash_new_index
```
**Symbols:**

```
ffffffff817e3760-ffffffff817e37db: tcf_hash_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tc_action *tcf_hash_lookup(u32 index, struct tcf_hashinfo *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81803150)
Location: net/sched/act_api.c:210
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_hash_check
  - net/sched/act_api.c:tcf_hash_search
  - net/sched/act_api.c:tcf_hash_new_index
```
**Symbols:**

```
ffffffff81803150-ffffffff818031cd: tcf_hash_lookup (STB_LOCAL)
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
<b>Return type changed. </b>
<code>struct tcf_common *</code> ➡️ <code>struct tc_action *</code>
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
