# Function: <code>__dma_async_device_channel_register</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1043
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff81706a40-ffffffff81706ba9: __dma_async_device_channel_register (STB_LOCAL)
ffffffff817085b0-ffffffff817085cf: __dma_async_device_channel_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff81723e80-ffffffff81723fdc: __dma_async_device_channel_register (STB_LOCAL)
ffffffff81c0437e-ffffffff81c0439a: __dma_async_device_channel_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff817050e0-ffffffff81705244: __dma_async_device_channel_register (STB_LOCAL)
ffffffff81bf5dd9-ffffffff81bf5df5: __dma_async_device_channel_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff817808c0-ffffffff81780a24: __dma_async_device_channel_register (STB_LOCAL)
ffffffff81cf3db8-ffffffff81cf3dd4: __dma_async_device_channel_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1038
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff818b73b0-ffffffff818b74fb: __dma_async_device_channel_register (STB_LOCAL)
ffffffff81ebbf6b-ffffffff81ebbf89: __dma_async_device_channel_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a04270)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff81a04270-ffffffff81a043d6: __dma_async_device_channel_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4d0d0)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff81a4d0d0-ffffffff81a4d236: __dma_async_device_channel_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dma_async_device_channel_register(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a98d40)
Location: drivers/dma/dmaengine.c:1039
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_channel_register
```
**Symbols:**

```
ffffffff81a98d40-ffffffff81a98ed5: __dma_async_device_channel_register (STB_LOCAL)
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
