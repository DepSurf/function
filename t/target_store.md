# Function: <code>target_store</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t target_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2275
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff817a1c20)
Location: drivers/xen/xen-balloon.c:188
Inline: False
```
**Symbols:**

```
ffffffff810b9020-ffffffff810b91ce: target_store (STB_LOCAL)
ffffffff81ca3f10-ffffffff81ca3f25: target_store.cold (STB_LOCAL)
ffffffff817a1c20-ffffffff817a1c94: target_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t target_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2297
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff818dbca0)
Location: drivers/xen/xen-balloon.c:188
Inline: False
```
**Symbols:**

```
ffffffff810cf980-ffffffff810cfb71: target_store (STB_LOCAL)
ffffffff81e5377f-ffffffff81e53794: target_store.cold (STB_LOCAL)
ffffffff818dbca0-ffffffff818dbd28: target_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t target_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2321
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81a2ee60)
Location: drivers/xen/xen-balloon.c:188
Inline: False
```
**Symbols:**

```
ffffffff810edd50-ffffffff810edf72: target_store (STB_LOCAL)
ffffffff82055c71-ffffffff82055c86: target_store.cold (STB_LOCAL)
ffffffff81a2ee60-ffffffff81a2eee8: target_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t target_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2706
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81a78620)
Location: drivers/xen/xen-balloon.c:188
Inline: False
```
**Symbols:**

```
ffffffff810f9e40-ffffffff810fa007: target_store (STB_LOCAL)
ffffffff820d4257-ffffffff820d426c: target_store.cold (STB_LOCAL)
ffffffff81a78620-ffffffff81a786a8: target_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t target_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2760
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81aca940)
Location: drivers/xen/xen-balloon.c:188
Inline: False
```
**Symbols:**

```
ffffffff81103260-ffffffff81103427: target_store (STB_LOCAL)
ffffffff821af12b-ffffffff821af140: target_store.cold (STB_LOCAL)
ffffffff81aca940-ffffffff81aca9c8: target_store (STB_LOCAL)
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
