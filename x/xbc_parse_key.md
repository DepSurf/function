# Function: <code>xbc_parse_key</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xbc_parse_key(char **k, char *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09fcd)
Location: lib/bootconfig.c:630
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff82d09fcd-ffffffff82d0a012: xbc_parse_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xbc_parse_key(char **k, char *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff75b4)
Location: lib/bootconfig.c:640
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff82ff75b4-ffffffff82ff75f9: xbc_parse_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xbc_parse_key(char **k, char *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83202094)
Location: lib/bootconfig.c:640
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff83202094-ffffffff832020d9: xbc_parse_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xbc_parse_key(char **k, char *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e97ec)
Location: lib/bootconfig.c:680
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff832e97ec-ffffffff832e9831: xbc_parse_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xbc_parse_key(char **k, char *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a1108)
Location: lib/bootconfig.c:745
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
```
**Symbols:**

```
ffffffff834a1108-ffffffff834a1155: xbc_parse_key (STB_LOCAL)
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
In lib/bootconfig.c (ffffffff83eda3c8)
Location: lib/bootconfig.c:745
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
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
In lib/bootconfig.c (ffffffff83700161)
Location: lib/bootconfig.c:745
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
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
In lib/bootconfig.c (ffffffff839339a1)
Location: lib/bootconfig.c:745
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
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
</ul>
