# Function: <code>cec_data_cancel</code>

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
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804360)
Location: drivers/media/cec/cec-adap.c:357
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff81804360-ffffffff81804406: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818459b0)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff818459b0-ffffffff81845a6b: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818772a0)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff818772a0-ffffffff8187736b: cec_data_cancel (STB_LOCAL)
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
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abec60)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffff800010abec60-ffff800010abed34: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0938)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
c0ba0938-c0ba0a24: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba04d0)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
c000000000ba04d0-c000000000ba060c: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0736)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffe0006c0736-ffffffe0006c07ee: cec_data_cancel (STB_LOCAL)
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
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f810)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff8181f810-ffffffff8181f8db: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6eb0)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff817e6eb0-ffffffff817e6f7b: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c750)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff8186c750-ffffffff8186c81b: cec_data_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data *data, u8 tx_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818866e0)
Location: drivers/media/cec/cec-adap.c:370
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
  - drivers/media/cec/cec-adap.c:cec_flush
```
**Symbols:**

```
ffffffff818866e0-ffffffff818867ab: cec_data_cancel (STB_LOCAL)
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
