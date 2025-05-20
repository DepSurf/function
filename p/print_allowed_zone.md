# Function: <code>print_allowed_zone</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816615f0)
Location: drivers/base/memory.c:392
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff816615f0-ffffffff8166163e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d020)
Location: drivers/base/memory.c:396
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff8169d020-ffffffff8169d06e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd960)
Location: drivers/base/memory.c:384
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff816bd960-ffffffff816bd9ae: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8870)
Location: drivers/base/memory.c:396
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff816f8870-ffffffff816f88be: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171cce0)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff8171cce0-ffffffff8171cd2e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d8c60)
Location: drivers/base/memory.c:310
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff817d8c60-ffffffff817d8cae: print_allowed_zone (STB_LOCAL)
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
In drivers/base/memory.c (ffffffff817ed8ca)
Location: drivers/base/memory.c:310
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff817d220a)
Location: drivers/base/memory.c:376
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff8185d32c)
Location: drivers/base/memory.c:383
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff819a4699)
Location: drivers/base/memory.c:388
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff81b166e9)
Location: drivers/base/memory.c:400
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff81b65459)
Location: drivers/base/memory.c:395
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
In drivers/base/memory.c (ffffffff81bb92d9)
Location: drivers/base/memory.c:435
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b1970)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
c0000000009b1970-c0000000009b1a00: print_allowed_zone (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e3010)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff816e3010-ffffffff816e305e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd650)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff816bd650-ffffffff816bd69e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817101a0)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff817101a0-ffffffff817101ee: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_allowed_zone(char *buf, int nid, long unsigned int start_pfn, long unsigned int nr_pages, int online_type, struct zone *default_zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172b300)
Location: drivers/base/memory.c:365
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff8172b300-ffffffff8172b34e: print_allowed_zone (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
