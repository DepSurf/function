# Function: <code>backend_reclaim_memory</code>

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
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8171f270)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:250
Inline: False
```
**Symbols:**

```
ffffffff8171f270-ffffffff8171f2ce: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8173c1d0)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff8173c1d0-ffffffff8173c22e: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8171fd30)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff8171fd30-ffffffff8171fd8e: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8179eb50)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff8179eb50-ffffffff8179ebae: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff818d8510)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff818d8510-ffffffff818d8576: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81a2ae80)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff81a2ae80-ffffffff81a2aee6: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81a74630)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff81a74630-ffffffff81a74696: backend_reclaim_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int backend_reclaim_memory(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81ac6790)
Location: drivers/xen/xenbus/xenbus_probe_backend.c:257
Inline: False
```
**Symbols:**

```
ffffffff81ac6790-ffffffff81ac67f6: backend_reclaim_memory (STB_LOCAL)
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
