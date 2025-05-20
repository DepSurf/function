# Function: <code>add_memory_driver_managed</code>

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
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e1960)
Location: mm/memory_hotplug.c:1156
Inline: False
```
**Symbols:**

```
ffffffff812e1960-ffffffff812e1a16: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ec8b0)
Location: mm/memory_hotplug.c:1167
Inline: False
```
**Symbols:**

```
ffffffff812ec8b0-ffffffff812ec96e: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7480)
Location: mm/memory_hotplug.c:1348
Inline: False
```
**Symbols:**

```
ffffffff812c7480-ffffffff812c7539: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c200)
Location: mm/memory_hotplug.c:1514
Inline: False
```
**Symbols:**

```
ffffffff8130c200-ffffffff8130c2b9: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81375200)
Location: mm/memory_hotplug.c:1482
Inline: False
```
**Symbols:**

```
ffffffff81375200-ffffffff813752ce: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2c20)
Location: mm/memory_hotplug.c:1480
Inline: False
```
**Symbols:**

```
ffffffff813f2c20-ffffffff813f2cee: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426660)
Location: mm/memory_hotplug.c:1455
Inline: False
```
**Symbols:**

```
ffffffff81426660-ffffffff8142672e: add_memory_driver_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_memory_driver_managed(int nid, u64 start, u64 size, const char *resource_name, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453820)
Location: mm/memory_hotplug.c:1637
Inline: False
```
**Symbols:**

```
ffffffff81453820-ffffffff814538ee: add_memory_driver_managed (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>mhp_t mhp_flags</code>
</li>
</ul>
</details>
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
