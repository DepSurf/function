# Function: <code>search_bpf_extables</code>

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
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa320)
Location: kernel/bpf/core.c:720
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff811fa320-ffffffff811fa37a: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9360)
Location: kernel/bpf/core.c:716
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff811f9360-ffffffff811f93d5: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa1f0)
Location: kernel/bpf/core.c:722
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff811fa1f0-ffffffff811fa265: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:723
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff81cb78e4-ffffffff81cb7900: search_bpf_extables.cold (STB_LOCAL)
ffffffff8122b8c0-ffffffff8122b934: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:726
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff81e68a20-ffffffff81e68a3d: search_bpf_extables.cold (STB_LOCAL)
ffffffff8126d390-ffffffff8126d418: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:734
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff8205f6ba-ffffffff8205f6d7: search_bpf_extables.cold (STB_LOCAL)
ffffffff812c2530-ffffffff812c25b8: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:735
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff820de5e1-ffffffff820de5fe: search_bpf_extables.cold (STB_LOCAL)
ffffffff812e93f0-ffffffff812e9478: search_bpf_extables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct exception_table_entry *search_bpf_extables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:778
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff821ba47b-ffffffff821ba498: search_bpf_extables.cold (STB_LOCAL)
ffffffff813077e0-ffffffff81307868: search_bpf_extables (STB_GLOBAL)
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
