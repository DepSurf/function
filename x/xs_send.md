# Function: <code>xs_send</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xs_send(struct xb_req_data *req, struct xsd_sockmsg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155e6d0)
Location: drivers/xen/xenbus/xenbus_xs.c:221
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8155e6d0-ffffffff8155e8a9: xs_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xs_send(struct xb_req_data *req, struct xsd_sockmsg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c29f0)
Location: drivers/xen/xenbus/xenbus_xs.c:221
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff815c29f0-ffffffff815c2bd3: xs_send (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815faf70)
Location: drivers/xen/xenbus/xenbus_xs.c:223
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff815faf70-ffffffff815fb133: xs_send.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616180)
Location: drivers/xen/xenbus/xenbus_xs.c:223
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81616180-ffffffff81616343: xs_send.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81649df0)
Location: drivers/xen/xenbus/xenbus_xs.c:224
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81649df0-ffffffff81649fba: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166c280)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8166c280-ffffffff8166c44a: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c630)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8171c630-ffffffff8171c6f1: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff817395f0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff817395f0-ffffffff817396b1: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171ccb0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8171ccb0-ffffffff8171ce8a: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8179ba20-ffffffff8179bc0d: xs_send.isra.0 (STB_LOCAL)
ffffffff81cf60c1-ffffffff81cf60d6: xs_send.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff818d4fe0-ffffffff818d5209: xs_send.isra.0 (STB_LOCAL)
ffffffff81ebe1a6-ffffffff81ebe1bb: xs_send.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81a27350-ffffffff81a27579: xs_send.isra.0 (STB_LOCAL)
ffffffff820948b8-ffffffff820948cd: xs_send.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81a70a70-ffffffff81a70c99: xs_send.isra.0 (STB_LOCAL)
ffffffff821156dc-ffffffff821156f1: xs_send.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff81ac2b70-ffffffff81ac2d99: xs_send.isra.0 (STB_LOCAL)
ffffffff821f3362-ffffffff821f3377: xs_send.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108367c0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffff8000108367c0-ffff800010836a00: xs_send.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816320f0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff816320f0-ffffffff816322ba: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816600c0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff816600c0-ffffffff8166028a: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167a6c0)
Location: drivers/xen/xenbus/xenbus_xs.c:227
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8167a6c0-ffffffff8167a883: xs_send.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
