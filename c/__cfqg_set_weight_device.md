# Function: <code>__cfqg_set_weight_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __cfqg_set_weight_device(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off, bool on_dfl, bool is_leaf_weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813de7a0)
Location: block/cfq-iosched.c:1757
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfqg_set_weight_device
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
```
**Symbols:**

```
ffffffff813de7a0-ffffffff813de93c: __cfqg_set_weight_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/cfq-iosched.c (ffffffff81424e40)
Location: block/cfq-iosched.c:1781
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfqg_set_weight_device
```
**Symbols:**

```
ffffffff81424e40-ffffffff81424fe4: __cfqg_set_weight_device.constprop.99 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/cfq-iosched.c (ffffffff81441400)
Location: block/cfq-iosched.c:1772
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfqg_set_weight_device
```
**Symbols:**

```
ffffffff81441400-ffffffff814415a4: __cfqg_set_weight_device.constprop.101 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/cfq-iosched.c (ffffffff814506e0)
Location: block/cfq-iosched.c:1777
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfqg_set_weight_device
```
**Symbols:**

```
ffffffff814506e0-ffffffff81450895: __cfqg_set_weight_device.constprop.103 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147bd00)
Location: block/cfq-iosched.c:1757
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfqg_set_weight_device
```
**Symbols:**

```
ffffffff8147bd00-ffffffff8147beb5: __cfqg_set_weight_device.constprop.103 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b04e0)
Location: block/cfq-iosched.c:1760
Inline: True
Direct callers:
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfqg_set_leaf_weight_device
  - block/cfq-iosched.c:cfqg_set_weight_device
```
**Symbols:**

```
ffffffff814b04e0-ffffffff814b06b1: __cfqg_set_weight_device.constprop.103 (STB_LOCAL)
```
</details>
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
</ul>
