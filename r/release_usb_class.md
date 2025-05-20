# Function: <code>release_usb_class</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81617630)
Location: drivers/usb/core/file.c:101
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff81617630-ffffffff81617662: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff816776f0)
Location: drivers/usb/core/file.c:102
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff816776f0-ffffffff81677722: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff816a53d0)
Location: drivers/usb/core/file.c:104
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff816a53d0-ffffffff816a5402: release_usb_class (STB_LOCAL)
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
In drivers/usb/core/file.c (ffffffff816ba7d9)
Location: drivers/usb/core/file.c:105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81725e50)
Location: drivers/usb/core/file.c:105
Inline: False
```
**Symbols:**

```
ffffffff81725e50-ffffffff81725e82: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81764c10)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff81764c10-ffffffff81764c42: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81789290)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff81789290-ffffffff817892c2: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817c7720)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff817c7720-ffffffff817c7752: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817f8240)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff817f8240-ffffffff817f8272: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff818c8696)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff818d3846)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff818b6da6)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff8194c7a4)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff81aa52c2)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff81c2bcb2)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffff81c92c42)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/usb/core/file.c (ffff800010a29274)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (c0aff24c)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (c000000000ae5670)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
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
In drivers/usb/core/file.c (ffffffe00064aca4)
Location: drivers/usb/core/file.c:105
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817b0620)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff817b0620-ffffffff817b0652: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817a22b0)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff817a22b0-ffffffff817a22e2: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817ed0c0)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff817ed0c0-ffffffff817ed0f2: release_usb_class (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_usb_class(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81807300)
Location: drivers/usb/core/file.c:105
Inline: False
Direct callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
**Symbols:**

```
ffffffff81807300-ffffffff81807332: release_usb_class (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
