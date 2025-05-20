# Function: <code>pm_runtime_set_memalloc_noio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81556030)
Location: drivers/base/power/runtime.c:193
Inline: False
Direct callers:
  - block/genhd.c:add_disk
  - block/genhd.c:del_gendisk
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81556030-ffffffff815560d8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a8070)
Location: drivers/base/power/runtime.c:193
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815a8070-ffffffff815a8118: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6840)
Location: drivers/base/power/runtime.c:195
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815d6840-ffffffff815d68e8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb240)
Location: drivers/base/power/runtime.c:195
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815eb240-ffffffff815eb2e8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81652620)
Location: drivers/base/power/runtime.c:195
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81652620-ffffffff816526c8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168df00)
Location: drivers/base/power/runtime.c:195
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8168df00-ffffffff8168dfa8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae110)
Location: drivers/base/power/runtime.c:186
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff816ae110-ffffffff816ae1b8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e8100)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff816e8100-ffffffff816e81a8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170c160)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8170c160-ffffffff8170c208: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c7400)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff817c7400-ffffffff817c74a8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dbe80)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff817dbe80-ffffffff817dbf28: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c0240)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff817c0240-ffffffff817c02e8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184a5b0)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8184a5b0-ffffffff8184a658: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8198f460)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8198f460-ffffffff8198f513: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81aff550)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81aff550-ffffffff81aff603: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4d900)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81b4d900-ffffffff81b4d9b3: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba5e80)
Location: drivers/base/power/runtime.c:218
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81ba5e80-ffffffff81ba5f33: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fae68)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffff8000108fae68-ffff8000108faf6c: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e6094)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
c09e6094-c09e613c: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000997b40)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
c000000000997b40-c000000000997ce0: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058a4b4)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffe00058a4b4-ffffffe00058a5aa: pm_runtime_set_memalloc_noio (STB_GLOBAL)
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
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d18b0)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff816d18b0-ffffffff816d1958: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816acbd0)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff816acbd0-ffffffff816acc72: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ffe20)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff816ffe20-ffffffff816ffec8: pm_runtime_set_memalloc_noio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_set_memalloc_noio(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171a3c0)
Location: drivers/base/power/runtime.c:217
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8171a3c0-ffffffff8171a467: pm_runtime_set_memalloc_noio (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
