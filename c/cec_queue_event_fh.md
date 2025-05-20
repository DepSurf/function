# Function: <code>cec_queue_event_fh</code>

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
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81803cf0)
Location: drivers/media/cec/cec-adap.c:86
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81803cf0-ffffffff81803ee9: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff818487f2-ffffffff81848805: cec_queue_event_fh.cold (STB_LOCAL)
ffffffff81845340-ffffffff81845530: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81876c20)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81876c20-ffffffff81876e1d: cec_queue_event_fh (STB_GLOBAL)
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
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abe598)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010abe598-ffff800010abe788: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba02b4)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba02b4-c0ba04b8: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000b9fba0)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000b9fba0-c000000000b9fe28: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c015c)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c015c-ffffffe0006c032a: cec_queue_event_fh (STB_GLOBAL)
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
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f190)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8181f190-ffffffff8181f38d: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6830)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817e6830-ffffffff817e6a2d: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c0d0)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186c0d0-ffffffff8186c2cd: cec_queue_event_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_queue_event_fh(struct cec_fh *fh, const struct cec_event *new_ev, u64 ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886060)
Location: drivers/media/cec/cec-adap.c:99
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event
  - drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81886060-ffffffff8188625d: cec_queue_event_fh (STB_GLOBAL)
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
