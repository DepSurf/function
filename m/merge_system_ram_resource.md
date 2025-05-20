# Function: <code>merge_system_ram_resource</code>

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
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad130)
Location: kernel/resource.c:1397
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810ad130-ffffffff810ad279: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ae330)
Location: kernel/resource.c:1450
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810ae330-ffffffff810ae479: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bfeb0)
Location: kernel/resource.c:1450
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810bfeb0-ffffffff810bfff9: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d7400)
Location: kernel/resource.c:1437
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810d7400-ffffffff810d7552: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6e40)
Location: kernel/resource.c:1429
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810f6e40-ffffffff810f6f92: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81103250)
Location: kernel/resource.c:1429
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81103250-ffffffff8110339c: merge_system_ram_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void merge_system_ram_resource(struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110cbb0)
Location: kernel/resource.c:1484
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8110cbb0-ffffffff8110ccfc: merge_system_ram_resource (STB_GLOBAL)
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
