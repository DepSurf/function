# Function: <code>nvmem_bin_attr_is_visible</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da620)
Location: drivers/nvmem/core.c:213
Inline: False
```
**Symbols:**

```
ffffffff819da620-ffffffff819da664: nvmem_bin_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d94b0)
Location: drivers/nvmem/core.c:303
Inline: False
```
**Symbols:**

```
ffffffff819d94b0-ffffffff819d94f4: nvmem_bin_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf580)
Location: drivers/nvmem/core.c:303
Inline: False
```
**Symbols:**

```
ffffffff819bf580-ffffffff819bf5c4: nvmem_bin_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:304
Inline: False
```
**Symbols:**

```
ffffffff81a6f1e0-ffffffff81a6f275: nvmem_bin_attr_is_visible (STB_LOCAL)
ffffffff81d344b8-ffffffff81d344e8: nvmem_bin_attr_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff81be03c0-ffffffff81be0469: nvmem_bin_attr_is_visible (STB_LOCAL)
ffffffff81f008f1-ffffffff81f00921: nvmem_bin_attr_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:309
Inline: False
```
**Symbols:**

```
ffffffff81d8c220-ffffffff81d8c2c9: nvmem_bin_attr_is_visible (STB_LOCAL)
ffffffff820aa8b2-ffffffff820aa8e2: nvmem_bin_attr_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:317
Inline: False
```
**Symbols:**

```
ffffffff81dfa8a0-ffffffff81dfa949: nvmem_bin_attr_is_visible (STB_LOCAL)
ffffffff8212bdee-ffffffff8212be1e: nvmem_bin_attr_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_is_visible(struct kobject *kobj, struct bin_attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:291
Inline: False
```
**Symbols:**

```
ffffffff81eb0cd0-ffffffff81eb0d79: nvmem_bin_attr_is_visible (STB_LOCAL)
ffffffff8220da9f-ffffffff8220dacf: nvmem_bin_attr_is_visible.cold (STB_LOCAL)
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
