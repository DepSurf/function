# Function: <code>read_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *read_reply(enum xsd_sockmsg_type *type, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd040)
Location: drivers/xen/xenbus/xenbus_xs.c:166
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff814cd040-ffffffff814cd213: read_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *read_reply(enum xsd_sockmsg_type *type, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151dba0)
Location: drivers/xen/xenbus/xenbus_xs.c:165
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8151dba0-ffffffff8151dd8b: read_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *read_reply(enum xsd_sockmsg_type *type, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a030)
Location: drivers/xen/xenbus/xenbus_xs.c:165
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
**Symbols:**

```
ffffffff8154a030-ffffffff8154a20a: read_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155ea88)
Location: drivers/xen/xenbus/xenbus_xs.c:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2dbf)
Location: drivers/xen/xenbus/xenbus_xs.c:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:202
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:202
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:203
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *read_reply(struct xb_req_data *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c200)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
**Symbols:**

```
ffffffff8171c200-ffffffff8171c335: read_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *read_reply(struct xb_req_data *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff817391b0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
**Symbols:**

```
ffffffff817391b0-ffffffff817392e5: read_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d06d)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179bdfd)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d542c)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a277cc)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a70eec)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3049)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:206
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
