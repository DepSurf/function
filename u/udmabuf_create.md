# Function: <code>udmabuf_create</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8170afa0)
Location: drivers/dma-buf/udmabuf.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8170afa0-ffffffff8170b37c: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff817465e0)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff817465e0-ffffffff81746999: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8176a730)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8176a730-ffffffff8176aae9: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8182c8b0)
Location: drivers/dma-buf/udmabuf.c:158
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8182c8b0-ffffffff8182cc91: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8183d9e0)
Location: drivers/dma-buf/udmabuf.c:157
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8183d9e0-ffffffff8183ddbb: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff81820b70)
Location: drivers/dma-buf/udmabuf.c:157
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff81820b70-ffffffff81820f54: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/udmabuf.c (0)
Location: drivers/dma-buf/udmabuf.c:163
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff818ab350-ffffffff818ab9b8: udmabuf_create (STB_LOCAL)
ffffffff81d0bdc3-ffffffff81d0be1a: udmabuf_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/udmabuf.c (0)
Location: drivers/dma-buf/udmabuf.c:166
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff819f5ac0-ffffffff819f61ee: udmabuf_create (STB_LOCAL)
ffffffff81ed4c23-ffffffff81ed4c7a: udmabuf_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/udmabuf.c (0)
Location: drivers/dma-buf/udmabuf.c:172
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff81b73080-ffffffff81b737b2: udmabuf_create (STB_LOCAL)
ffffffff8209b94d-ffffffff8209b9b7: udmabuf_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6b20)
Location: drivers/dma-buf/udmabuf.c:199
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff81bc6b20-ffffffff81bc6f27: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int udmabuf_create(struct miscdevice *device, struct udmabuf_create_list *head, struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b660)
Location: drivers/dma-buf/udmabuf.c:197
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff81c1b660-ffffffff81c1ba93: udmabuf_create (STB_LOCAL)
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
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffff80001096c9f0)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffff80001096c9f0-ffff80001096cd84: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (c0a41edc)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
c0a41edc-c0a4228c: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (c000000000a25140)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
c000000000a25140-c000000000a25624: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffe0005d724e)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffe0005d724e-ffffffe0005d7562: udmabuf_create (STB_LOCAL)
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
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8171ee20)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8171ee20-ffffffff8171f1d9: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff816f8250)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff816f8250-ffffffff816f8609: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff8175dbf0)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff8175dbf0-ffffffff8175dfa9: udmabuf_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int udmabuf_create(const struct udmabuf_create_list *head, const struct udmabuf_create_item *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffff81779250)
Location: drivers/dma-buf/udmabuf.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
**Symbols:**

```
ffffffff81779250-ffffffff81779609: udmabuf_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct miscdevice *device</code>
</li>
<li>
<b>Param reordered. </b>
<code>head, list</code> ➡️ <code>device, head, list</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct udmabuf_create_list *head</code> ➡️ <code>struct udmabuf_create_list *head</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct udmabuf_create_item *list</code> ➡️ <code>struct udmabuf_create_item *list</code>
</li>
</ul>
</details>
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
