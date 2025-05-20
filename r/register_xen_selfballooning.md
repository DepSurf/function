# Function: <code>register_xen_selfballooning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff814d2c60)
Location: drivers/xen/xen-selfballoon.c:516
Inline: False
```
**Symbols:**

```
ffffffff814d2c60-ffffffff814d2c7b: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff81523980)
Location: drivers/xen/xen-selfballoon.c:515
Inline: False
```
**Symbols:**

```
ffffffff81523980-ffffffff8152399b: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff8154fe40)
Location: drivers/xen/xen-selfballoon.c:515
Inline: False
```
**Symbols:**

```
ffffffff8154fe40-ffffffff8154fe5b: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff815645b0)
Location: drivers/xen/xen-selfballoon.c:515
Inline: False
Direct callers:
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff815645b0-ffffffff815645cb: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff815c8740)
Location: drivers/xen/xen-selfballoon.c:516
Inline: False
Direct callers:
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff815c8740-ffffffff815c875b: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff81600fd0)
Location: drivers/xen/xen-selfballoon.c:516
Inline: False
Direct callers:
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff81600fd0-ffffffff81600feb: register_xen_selfballooning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_xen_selfballooning(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff8161c0c0)
Location: drivers/xen/xen-selfballoon.c:516
Inline: False
Direct callers:
  - drivers/xen/xen-balloon.c:xen_balloon_init
```
**Symbols:**

```
ffffffff8161c0c0-ffffffff8161c0db: register_xen_selfballooning (STB_GLOBAL)
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
