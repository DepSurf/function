# Function: <code>__dma_async_device_channel_unregister</code>

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
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81706750)
Location: drivers/dma/dmaengine.c:1109
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81706750-ffffffff8170683e: __dma_async_device_channel_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81723ac0)
Location: drivers/dma/dmaengine.c:1106
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81723ac0-ffffffff81723b7e: __dma_async_device_channel_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81704d30)
Location: drivers/dma/dmaengine.c:1107
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81704d30-ffffffff81704dee: __dma_async_device_channel_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1107
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81780780-ffffffff81780857: __dma_async_device_channel_unregister (STB_LOCAL)
ffffffff81cf3d9d-ffffffff81cf3db2: __dma_async_device_channel_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1102
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff818b7250-ffffffff818b731b: __dma_async_device_channel_unregister (STB_LOCAL)
ffffffff81ebbf56-ffffffff81ebbf6b: __dma_async_device_channel_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1103
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81a040f0-ffffffff81a041bb: __dma_async_device_channel_unregister (STB_LOCAL)
ffffffff820937a3-ffffffff820937b8: __dma_async_device_channel_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1103
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81a4cf50-ffffffff81a4d01b: __dma_async_device_channel_unregister (STB_LOCAL)
ffffffff821144af-ffffffff821144c4: __dma_async_device_channel_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __dma_async_device_channel_unregister(struct dma_device *device, struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1103
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_channel_unregister
```
**Symbols:**

```
ffffffff81a98ba0-ffffffff81a98c83: __dma_async_device_channel_unregister (STB_LOCAL)
ffffffff821f1e99-ffffffff821f1eae: __dma_async_device_channel_unregister.cold (STB_LOCAL)
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
