# Function: <code>__acpi_device_uevent_modalias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8147c4e7)
Location: drivers/acpi/device_sysfs.c:240
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff8147c4e7-ffffffff8147c5cf: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814cac36)
Location: drivers/acpi/device_sysfs.c:240
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff814cac36-ffffffff814cad13: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ecb62)
Location: drivers/acpi/device_sysfs.c:240
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff814ecb62-ffffffff814ecc3f: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814f94d0)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff814f94d0-ffffffff814f95bd: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8153ad60)
Location: drivers/acpi/device_sysfs.c:244
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff8153ad60-ffffffff8153ae74: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81570bd0)
Location: drivers/acpi/device_sysfs.c:244
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff81570bd0-ffffffff81570cda: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815887a0)
Location: drivers/acpi/device_sysfs.c:248
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815887a0-ffffffff815888aa: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b9470)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815b9470-ffffffff815b9584: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815da6b0)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815da6b0-ffffffff815da7c4: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81684a25)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff81684750-ffffffff81684826: __acpi_device_uevent_modalias.part.0 (STB_LOCAL)
ffffffff81684d50-ffffffff81684dae: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816a2a30)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff816a2a30-ffffffff816a2b15: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81685820)
Location: drivers/acpi/device_sysfs.c:241
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff81685820-ffffffff81685905: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816faae0)
Location: drivers/acpi/device_sysfs.c:241
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff816faae0-ffffffff816fac03: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81827f70)
Location: drivers/acpi/device_sysfs.c:242
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff81827f70-ffffffff8182808c: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81959fa0)
Location: drivers/acpi/device_sysfs.c:242
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff81959fa0-ffffffff8195a0bc: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(const struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff819a0400)
Location: drivers/acpi/device_sysfs.c:242
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff819a0400-ffffffff819a051c: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_device_uevent_modalias(const struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff819e8a70)
Location: drivers/acpi/device_sysfs.c:240
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff819e8a70-ffffffff819e8b8c: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffff800010766bf8)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffff800010766bf8-ffff800010766d30: __acpi_device_uevent_modalias (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815cce80)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815cce80-ffffffff815ccf94: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b6a00)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815b6a00-ffffffff815b6b14: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815ce990)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815ce990-ffffffff815ceaa4: __acpi_device_uevent_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __acpi_device_uevent_modalias(struct acpi_device *adev, struct kobj_uevent_env *env);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815e8850)
Location: drivers/acpi/device_sysfs.c:240
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/acpi/bus.c:acpi_device_uevent
```
**Symbols:**

```
ffffffff815e8850-ffffffff815e8964: __acpi_device_uevent_modalias (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device *adev</code> ➡️ <code>const struct acpi_device *adev</code>
</li>
</ul>
</details>
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
