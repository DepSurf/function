# Function: <code>register_memory_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81819b4e)
Location: mm/memory_hotplug.c:130
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818946f0)
Location: mm/memory_hotplug.c:150
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c8de0)
Location: mm/memory_hotplug.c:150
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81900370)
Location: mm/memory_hotplug.c:100
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8198a310)
Location: mm/memory_hotplug.c:102
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6c35)
Location: mm/memory_hotplug.c:102
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a22085)
Location: mm/memory_hotplug.c:102
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91ee5)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac9675)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0470)
Location: mm/memory_hotplug.c:103
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff812e0470-ffffffff812e0517: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812eb380)
Location: mm/memory_hotplug.c:103
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff812eb380-ffffffff812eb427: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7360)
Location: mm/memory_hotplug.c:113
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff812c7360-ffffffff812c7427: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c0e0)
Location: mm/memory_hotplug.c:178
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff8130c0e0-ffffffff8130c1a4: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813750e0)
Location: mm/memory_hotplug.c:195
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff813750e0-ffffffff813751ab: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2ae0)
Location: mm/memory_hotplug.c:187
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff813f2ae0-ffffffff813f2bab: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426520)
Location: mm/memory_hotplug.c:186
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff81426520-ffffffff814265eb: register_memory_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *register_memory_resource(u64 start, u64 size, const char *resource_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814536e0)
Location: mm/memory_hotplug.c:254
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff814536e0-ffffffff814537ab: register_memory_resource (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d484)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000043047c)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a684e5)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24fa5)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad48f5)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0dd5)
Location: mm/memory_hotplug.c:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
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
