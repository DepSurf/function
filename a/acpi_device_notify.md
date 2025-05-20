# Function: <code>acpi_device_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147dfa2)
Location: drivers/acpi/bus.c:418
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff8147dfa2-ffffffff8147dfbd: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cc757)
Location: drivers/acpi/bus.c:430
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff814cc757-ffffffff814cc772: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ee685)
Location: drivers/acpi/bus.c:440
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff814ee685-ffffffff814ee6a0: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fb415)
Location: drivers/acpi/bus.c:426
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff814fb3f0-ffffffff814fb40b: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153d095)
Location: drivers/acpi/bus.c:453
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff8153d060-ffffffff8153d081: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81572f35)
Location: drivers/acpi/bus.c:460
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
**Symbols:**

```
ffffffff81572f00-ffffffff81572f21: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158ab25)
Location: drivers/acpi/bus.c:429
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff8158c53a)
Location: drivers/acpi/glue.c:299
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff8158aaf0-ffffffff8158ab11: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bb8b5)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815bd2ba)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815bb880-ffffffff815bb8a1: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dcb75)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815de57a)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815dcb40-ffffffff815dcb61: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687285)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff81688e10)
Location: drivers/acpi/glue.c:298
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff81687250-ffffffff81687271: acpi_device_notify (STB_LOCAL)
ffffffff81688e10-ffffffff81688f09: acpi_device_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a4f95)
Location: drivers/acpi/bus.c:420
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff816a69e0)
Location: drivers/acpi/glue.c:298
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff816a4f60-ffffffff816a4f81: acpi_device_notify (STB_LOCAL)
ffffffff816a69e0-ffffffff816a6ad9: acpi_device_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687d15)
Location: drivers/acpi/bus.c:499
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff81689717)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff81687ce0-ffffffff81687d01: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_device_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816feaa0)
Location: drivers/acpi/glue.c:288
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816feaa0-ffffffff816fec8b: acpi_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_device_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8182c460)
Location: drivers/acpi/glue.c:289
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8182c460-ffffffff8182c61d: acpi_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_device_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8195f070)
Location: drivers/acpi/glue.c:352
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8195f070-ffffffff8195f23d: acpi_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_device_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819a5460)
Location: drivers/acpi/glue.c:352
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff819a5460-ffffffff819a5636: acpi_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_device_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819edde0)
Location: drivers/acpi/glue.c:352
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff819edde0-ffffffff819edfb6: acpi_device_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010768dc0)
Location: drivers/acpi/bus.c:416
Inline: True
```
```
In drivers/acpi/glue.c (ffff80001076a9d8)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffff800010768dc0-ffff800010768dfc: acpi_device_notify (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cf1c5)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815d0a5a)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815cf190-ffffffff815cf1b1: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b8d85)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815ba61a)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815b8d50-ffffffff815b8d71: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d0e55)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815d285a)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815d0e20-ffffffff815d0e41: acpi_device_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_device_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ead15)
Location: drivers/acpi/bus.c:416
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_notify_fixed
```
```
In drivers/acpi/glue.c (ffffffff815ec71a)
Location: drivers/acpi/glue.c:298
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
**Symbols:**

```
ffffffff815eace0-ffffffff815ead01: acpi_device_notify (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>acpi_handle handle</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 event</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
