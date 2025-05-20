# Function: <code>inherit_ruleset</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inherit_ruleset(const struct landlock_ruleset * parent, const struct landlock_ruleset * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81537db0)
Location: security/landlock/ruleset.c:312
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff81537db0-ffffffff81537eed: inherit_ruleset (STB_LOCAL)
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
In security/landlock/ruleset.c (ffffffff815969c7)
Location: security/landlock/ruleset.c:312
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inherit_ruleset(const struct landlock_ruleset * parent, const struct landlock_ruleset * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638930)
Location: security/landlock/ruleset.c:314
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff81638930-ffffffff81638a59: inherit_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inherit_ruleset(const struct landlock_ruleset * parent, const struct landlock_ruleset * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816eff70)
Location: security/landlock/ruleset.c:314
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff816eff70-ffffffff816f0099: inherit_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inherit_ruleset(const struct landlock_ruleset * parent, const struct landlock_ruleset * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a310)
Location: security/landlock/ruleset.c:314
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff8172a310-ffffffff8172a439: inherit_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inherit_ruleset(const struct landlock_ruleset * parent, const struct landlock_ruleset * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176b880)
Location: security/landlock/ruleset.c:440
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff8176b880-ffffffff8176b988: inherit_ruleset (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
