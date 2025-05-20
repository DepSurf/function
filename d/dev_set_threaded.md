# Function: <code>dev_set_threaded</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8030)
Location: net/core/dev.c:6845
Inline: False
Direct callers:
  - net/core/net-sysfs.c:modify_napi_threaded
```
**Symbols:**

```
ffffffff819e8030-ffffffff819e8130: dev_set_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99030)
Location: net/core/dev.c:6831
Inline: False
Direct callers:
  - net/core/net-sysfs.c:modify_napi_threaded
```
**Symbols:**

```
ffffffff81a99030-ffffffff81a99130: dev_set_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0d040)
Location: net/core/dev.c:6317
Inline: False
Direct callers:
  - net/core/net-sysfs.c:threaded_store
```
**Symbols:**

```
ffffffff81c0d040-ffffffff81c0d154: dev_set_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbcc50)
Location: net/core/dev.c:6306
Inline: False
Direct callers:
  - net/core/net-sysfs.c:threaded_store
```
**Symbols:**

```
ffffffff81dbcc50-ffffffff81dbcd64: dev_set_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2d460)
Location: net/core/dev.c:6286
Inline: False
Direct callers:
  - net/core/net-sysfs.c:threaded_store
```
**Symbols:**

```
ffffffff81e2d460-ffffffff81e2d59c: dev_set_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_set_threaded(struct net_device *dev, bool threaded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeb750)
Location: net/core/dev.c:6368
Inline: False
Direct callers:
  - net/core/net-sysfs.c:threaded_store
```
**Symbols:**

```
ffffffff81eeb750-ffffffff81eeb898: dev_set_threaded (STB_GLOBAL)
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
