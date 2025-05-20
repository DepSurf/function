# Function: <code>merge_ruleset</code>

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
int merge_ruleset(const struct landlock_ruleset * dst, const struct landlock_ruleset * src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81537ef0)
Location: security/landlock/ruleset.c:259
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff81537ef0-ffffffff81538056: merge_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int merge_ruleset(const struct landlock_ruleset * dst, const struct landlock_ruleset * src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815965b0)
Location: security/landlock/ruleset.c:259
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff815965b0-ffffffff81596716: merge_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int merge_ruleset(const struct landlock_ruleset * dst, const struct landlock_ruleset * src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638a60)
Location: security/landlock/ruleset.c:261
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff81638a60-ffffffff81638bc3: merge_ruleset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int merge_ruleset(const struct landlock_ruleset * dst, const struct landlock_ruleset * src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816efdf0)
Location: security/landlock/ruleset.c:261
Inline: False
Direct callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
```
**Symbols:**

```
ffffffff816efdf0-ffffffff816eff53: merge_ruleset (STB_LOCAL)
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
In security/landlock/ruleset.c (ffffffff8172a802)
Location: security/landlock/ruleset.c:261
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
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
In security/landlock/ruleset.c (ffffffff8176be91)
Location: security/landlock/ruleset.c:366
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
