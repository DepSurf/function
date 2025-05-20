# Function: <code>stack_depot_init</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: include/linux/stackdepot.h:27
Inline: True
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
In init/main.c (0)
Location: include/linux/stackdepot.h:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int stack_depot_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:203
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff81ea4959-ffffffff81ea49b8: stack_depot_init.cold (STB_LOCAL)
ffffffff8176f470-ffffffff8176f4c4: stack_depot_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int stack_depot_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:231
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8208d507-ffffffff8208d539: stack_depot_init.cold (STB_LOCAL)
ffffffff8189eeb0-ffffffff8189efad: stack_depot_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int stack_depot_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:170
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8210d8a5-ffffffff8210d8d7: stack_depot_init.cold (STB_LOCAL)
ffffffff818e1380-ffffffff818e1475: stack_depot_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int stack_depot_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:231
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff821eb481-ffffffff821eb4b3: stack_depot_init.cold (STB_LOCAL)
ffffffff81927fc0-ffffffff819280d0: stack_depot_init (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
