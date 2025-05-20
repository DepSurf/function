# Function: <code>overcommit_policy_handler</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127de30)
Location: mm/util.c:767
Inline: False
```
**Symbols:**

```
ffffffff8127de30-ffffffff8127def3: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282fa0)
Location: mm/util.c:757
Inline: False
```
**Symbols:**

```
ffffffff81282fa0-ffffffff81283063: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c1150)
Location: mm/util.c:788
Inline: False
```
**Symbols:**

```
ffffffff812c1150-ffffffff812c1221: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131e0f0)
Location: mm/util.c:913
Inline: False
```
**Symbols:**

```
ffffffff8131e0f0-ffffffff8131e1f2: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391b30)
Location: mm/util.c:806
Inline: False
```
**Symbols:**

```
ffffffff81391b30-ffffffff81391c32: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c4530)
Location: mm/util.c:829
Inline: False
```
**Symbols:**

```
ffffffff813c4530-ffffffff813c4632: overcommit_policy_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int overcommit_policy_handler(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813eefb0)
Location: mm/util.c:837
Inline: False
```
**Symbols:**

```
ffffffff813eefb0-ffffffff813ef0b2: overcommit_policy_handler (STB_GLOBAL)
```
</details>
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
