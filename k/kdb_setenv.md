# Function: <code>kdb_setenv</code>

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
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a840)
Location: kernel/debug/kdb/kdb_main.c:303
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff8119a840-ffffffff8119a95b: kdb_setenv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811c47b0)
Location: kernel/debug/kdb/kdb_main.c:302
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff811c47b0-ffffffff811c49b4: kdb_setenv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811f8030)
Location: kernel/debug/kdb/kdb_main.c:354
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff811f8030-ffffffff811f8209: kdb_setenv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8123f450)
Location: kernel/debug/kdb/kdb_main.c:354
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff8123f450-ffffffff8123f629: kdb_setenv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff812564c0)
Location: kernel/debug/kdb/kdb_main.c:354
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff812564c0-ffffffff81256699: kdb_setenv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kdb_setenv(const char *var, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81270340)
Location: kernel/debug/kdb/kdb_main.c:353
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_set
```
**Symbols:**

```
ffffffff81270340-ffffffff81270519: kdb_setenv (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
