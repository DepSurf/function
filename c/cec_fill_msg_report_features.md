# Function: <code>cec_fill_msg_report_features</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8180633a)
Location: drivers/media/cec/cec-adap.c:1746
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845190)
Location: drivers/media/cec/cec-adap.c:1807
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81845190-ffffffff81845208: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81876a70)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81876a70-ffffffff81876ae8: cec_fill_msg_report_features (STB_LOCAL)
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
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abe3a0)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffff800010abe3a0-ffff800010abe450: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba00d0)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c0ba00d0-c0ba0174: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000b9f960)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c000000000b9f960-c000000000b9f9f0: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006bff84)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffe0006bff84-ffffffe0006c0028: cec_fill_msg_report_features (STB_LOCAL)
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
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181efe0)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff8181efe0-ffffffff8181f058: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6680)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff817e6680-ffffffff817e66f8: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186bf20)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff8186bf20-ffffffff8186bf98: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter *adap, struct cec_msg *msg, unsigned int la_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81885eb0)
Location: drivers/media/cec/cec-adap.c:1824
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81885eb0-ffffffff81885f28: cec_fill_msg_report_features (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
