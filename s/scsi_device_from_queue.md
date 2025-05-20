# Function: <code>scsi_device_from_queue</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635080)
Location: drivers/scsi/scsi_lib.c:2155
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81635080-ffffffff816350d6: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649e30)
Location: drivers/scsi/scsi_lib.c:2235
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81649e30-ffffffff81649e86: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2f80)
Location: drivers/scsi/scsi_lib.c:2313
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff816b2f80-ffffffff816b2fd6: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef190)
Location: drivers/scsi/scsi_lib.c:2329
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff816ef190-ffffffff816ef1ee: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713e40)
Location: drivers/scsi/scsi_lib.c:1923
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81713e40-ffffffff81713e76: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174f540)
Location: drivers/scsi/scsi_lib.c:1876
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff8174f540-ffffffff8174f57a: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81773720)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81773720-ffffffff8177376b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81835b90)
Location: drivers/scsi/scsi_lib.c:1919
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff81835b90-ffffffff81835bdf: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81848de0)
Location: drivers/scsi/scsi_lib.c:1943
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff81848de0-ffffffff81848e2f: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182c220)
Location: drivers/scsi/scsi_lib.c:1959
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff8182c220-ffffffff8182c26f: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b7dc0)
Location: drivers/scsi/scsi_lib.c:1949
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff818b7dc0-ffffffff818b7e0f: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819ff430)
Location: drivers/scsi/scsi_lib.c:2004
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff819ff430-ffffffff819ff488: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b81f00)
Location: drivers/scsi/scsi_lib.c:2009
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff81b81f00-ffffffff81b81f58: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd5c10)
Location: drivers/scsi/scsi_lib.c:2015
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff81bd5c10-ffffffff81bd5c6b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2a860)
Location: drivers/scsi/scsi_lib.c:2012
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
  - drivers/scsi/scsi_dh.c:scsi_dh_activate
```
**Symbols:**

```
ffffffff81c2a860-ffffffff81c2a8b7: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976d30)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffff800010976d30-ffff800010976d94: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4b44c)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
c0a4b44c-c0a4b4a4: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a316f0)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
c000000000a316f0-c000000000a31774: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005df202)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffe0005df202-ffffffe0005df252: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727e10)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81727e10-ffffffff81727e5b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81701240)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81701240-ffffffff8170128b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81766be0)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff81766be0-ffffffff81766c2b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct scsi_device *scsi_device_from_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817822f0)
Location: drivers/scsi/scsi_lib.c:1922
Inline: True
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:scsi_dh_set_params
```
**Symbols:**

```
ffffffff817822f0-ffffffff8178233b: scsi_device_from_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
