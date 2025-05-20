# Function: <code>find_governor_by_name</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff8171df30)
Location: drivers/watchdog/watchdog_pretimeout.c:44
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff8171df30-ffffffff8171df85: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81736130)
Location: drivers/watchdog/watchdog_pretimeout.c:44
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff81736130-ffffffff81736185: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff817a7eb0)
Location: drivers/watchdog/watchdog_pretimeout.c:44
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff817a7eb0-ffffffff817a7f05: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff817ef940)
Location: drivers/watchdog/watchdog_pretimeout.c:44
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff817ef940-ffffffff817ef995: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff8181b830)
Location: drivers/watchdog/watchdog_pretimeout.c:44
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff8181b830-ffffffff8181b885: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff8185daa0)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff8185daa0-ffffffff8185daf8: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff8188f5d0)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff8188f5d0-ffffffff8188f628: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff8195e2af)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81964bdf)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81948fff)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff819ee0ff)
Location: drivers/watchdog/watchdog_pretimeout.c:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81b54b6f)
Location: drivers/watchdog/watchdog_pretimeout.c:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81ced93f)
Location: drivers/watchdog/watchdog_pretimeout.c:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81d5667f)
Location: drivers/watchdog/watchdog_pretimeout.c:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81e0d5be)
Location: drivers/watchdog/watchdog_pretimeout.c:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
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
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffff800010ae0ea0)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffff800010ae0ea0-ffff800010ae0f28: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (c0bc1ec0)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
c0bc1ec0-c0bc1f2c: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (c000000000bc8b90)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
c000000000bc8b90-c000000000bc8c54: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffe0006d80ca)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffe0006d80ca-ffffffe0006d8134: find_governor_by_name (STB_LOCAL)
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
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81835450)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff81835450-ffffffff818354a8: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff817fcae0)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff817fcae0-ffffffff817fcb38: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81884a80)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff81884a80-ffffffff81884ad8: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct governor_priv *find_governor_by_name(const char *gov_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff818a0540)
Location: drivers/watchdog/watchdog_pretimeout.c:39
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
```
**Symbols:**

```
ffffffff818a0540-ffffffff818a0598: find_governor_by_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
