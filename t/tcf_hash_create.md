# Function: <code>tcf_hash_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_hash_create(u32 index, struct nlattr *est, struct tc_action *a, int size, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747570)
Location: net/sched/act_api.c:246
Inline: False
```
**Symbols:**

```
ffffffff81747570-ffffffff81747745: tcf_hash_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcf_hash_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b48f0)
Location: net/sched/act_api.c:246
Inline: False
```
**Symbols:**

```
ffffffff817b48f0-ffffffff817b4afa: tcf_hash_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcf_hash_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e41b0)
Location: net/sched/act_api.c:251
Inline: False
```
**Symbols:**

```
ffffffff817e41b0-ffffffff817e43bf: tcf_hash_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_hash_create(struct tc_action_net *tn, u32 index, struct nlattr *est, struct tc_action **a, const struct tc_action_ops *ops, int bind, bool cpustats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81803bf0)
Location: net/sched/act_api.c:278
Inline: False
```
**Symbols:**

```
ffffffff81803bf0-ffffffff81803dfa: tcf_hash_create (STB_GLOBAL)
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
<code>struct tc_action_net *tn</code>
</li>
<li>
<b>Param added. </b>
<code>const struct tc_action_ops *ops</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>index, est, a, size, bind, cpustats</code> ➡️ <code>tn, index, est, a, ops, bind, cpustats</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct tc_action *a</code> ➡️ <code>struct tc_action **a</code>
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
