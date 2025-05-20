# Function: <code>unregister_memory_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561a70)
Location: drivers/base/memory.c:714
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81561a70-ffffffff81561b02: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b6360)
Location: drivers/base/memory.c:760
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff815b6360-ffffffff815b640c: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e5680)
Location: drivers/base/memory.c:761
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff815e5680-ffffffff815e572c: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815fa100)
Location: drivers/base/memory.c:764
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff815fa100-ffffffff815fa1a3: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816622a0)
Location: drivers/base/memory.c:775
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff816622a0-ffffffff81662343: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169da90)
Location: drivers/base/memory.c:783
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8169da90-ffffffff8169db2b: unregister_memory_section (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_memory_section(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816be200)
Location: drivers/base/memory.c:768
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff816be200-ffffffff816be29b: unregister_memory_section (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
</ul>
