# Function: <code>__vme_register_driver_bus</code>

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
In drivers/vme/vme.c (ffffffff816f16ce)
Location: drivers/vme/vme.c:1473
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (ffffffff81756714)
Location: drivers/vme/vme.c:1487
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (ffffffff81782cf4)
Location: drivers/vme/vme.c:1490
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (ffffffff817a1ac6)
Location: drivers/vme/vme.c:1882
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (ffffffff81818be6)
Location: drivers/vme/vme.c:1856
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1856
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1856
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff819d51b0)
Location: drivers/vme/vme.c:1852
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff819d51b0-ffffffff819d53bf: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff819d4d30)
Location: drivers/vme/vme.c:1843
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff819d4d30-ffffffff819d4f3f: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff819b9fe0)
Location: drivers/vme/vme.c:1843
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff819b9fe0-ffffffff819ba1ef: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81a690e0)
Location: drivers/vme/vme.c:1843
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81a690e0-ffffffff81a692ef: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81bdaaa0)
Location: drivers/vme/vme.c:1843
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81bdaaa0-ffffffff81bdacc9: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6c8a0)
Location: drivers/staging/vme_user/vme.c:1843
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81d6c8a0-ffffffff81d6cac9: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd9c90)
Location: drivers/staging/vme_user/vme.c:1843
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81dd9c90-ffffffff81dd9eb9: __vme_register_driver_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vme_register_driver_bus(struct vme_driver *drv, struct vme_bridge *bridge, unsigned int ndevs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e912e0)
Location: drivers/staging/vme_user/vme.c:1811
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81e912e0-ffffffff81e9152c: __vme_register_driver_bus (STB_LOCAL)
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe0007342ec)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
```
</details>
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1852
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_register_driver
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
