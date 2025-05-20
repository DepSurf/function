# Function: <code>xbc_parse_kv</code>

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
int xbc_parse_kv(char **k, char *v, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09e54)
Location: lib/bootconfig.c:585
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff82d09e54-ffffffff82d09fcd: xbc_parse_kv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xbc_parse_kv(char **k, char *v, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff7414)
Location: lib/bootconfig.c:593
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff82ff7414-ffffffff82ff75b4: xbc_parse_kv (STB_LOCAL)
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
In lib/bootconfig.c (ffffffff83202840)
Location: lib/bootconfig.c:593
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
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
In lib/bootconfig.c (ffffffff832e9fef)
Location: lib/bootconfig.c:627
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
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
In lib/bootconfig.c (ffffffff834a1298)
Location: lib/bootconfig.c:692
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
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
In lib/bootconfig.c (ffffffff83eda4ba)
Location: lib/bootconfig.c:692
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xbc_parse_kv(char **k, char *v, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff836ffe10)
Location: lib/bootconfig.c:692
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
```
**Symbols:**

```
ffffffff836ffe10-ffffffff83700021: xbc_parse_kv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xbc_parse_kv(char **k, char *v, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933650)
Location: lib/bootconfig.c:692
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
```
**Symbols:**

```
ffffffff83933650-ffffffff83933861: xbc_parse_kv (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
