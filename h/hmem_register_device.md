# Function: <code>hmem_register_device</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hmem_register_device(int target_nid, struct resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/hmem/device.c (0)
Location: drivers/dax/hmem/device.c:11
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81c1609c-ffffffff81c16117: hmem_register_device.cold (STB_LOCAL)
ffffffff81834f20-ffffffff81835034: hmem_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hmem_register_device(int target_nid, struct resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/hmem/device.c (0)
Location: drivers/dax/hmem/device.c:11
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81c07e08-ffffffff81c07e83: hmem_register_device.cold (STB_LOCAL)
ffffffff818180f0-ffffffff81818204: hmem_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hmem_register_device(int target_nid, struct resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/hmem/device.c (0)
Location: drivers/dax/hmem/device.c:11
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81d0b9d4-ffffffff81d0ba64: hmem_register_device.cold (STB_LOCAL)
ffffffff818a2760-ffffffff818a288b: hmem_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hmem_register_device(int target_nid, struct resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/hmem/device.c (0)
Location: drivers/dax/hmem/device.c:11
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81ed47ff-ffffffff81ed488f: hmem_register_device.cold (STB_LOCAL)
ffffffff819ebf60-ffffffff819ec0a0: hmem_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hmem_register_device(int target_nid, struct resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/hmem/device.c (0)
Location: drivers/dax/hmem/device.c:18
Inline: False
Direct callers:
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff8209b676-ffffffff8209b68b: hmem_register_device.cold (STB_LOCAL)
ffffffff81b68b50-ffffffff81b68d7d: hmem_register_device (STB_GLOBAL)
```
</details>
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
</ul>
