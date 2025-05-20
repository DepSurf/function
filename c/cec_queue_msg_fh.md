# Function: <code>cec_queue_msg_fh</code>

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
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804120)
Location: drivers/media/cec/cec-adap.c:215
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff81804120-ffffffff8180424b: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845760)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff81845760-ffffffff8184588b: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877050)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff81877050-ffffffff8187717b: cec_queue_msg_fh (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abea10)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffff800010abea10-ffff800010abeb24: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0724)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
c0ba0724-c0ba0828: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0170)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
c000000000ba0170-c000000000ba0308: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c051e)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffe0006c051e-ffffffe0006c0638: cec_queue_msg_fh (STB_LOCAL)
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
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f5c0)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff8181f5c0-ffffffff8181f6eb: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6c60)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff817e6c60-ffffffff817e6d8b: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c500)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff8186c500-ffffffff8186c62b: cec_queue_msg_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_queue_msg_fh(struct cec_fh *fh, const struct cec_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886490)
Location: drivers/media/cec/cec-adap.c:228
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_queue_msg_monitor
```
**Symbols:**

```
ffffffff81886490-ffffffff818865bb: cec_queue_msg_fh (STB_LOCAL)
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
