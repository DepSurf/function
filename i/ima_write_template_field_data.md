# Function: <code>ima_write_template_field_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81399e00)
Location: security/integrity/ima/ima_template_lib.c:34
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
```
**Symbols:**

```
ffffffff81399e00-ffffffff81399eba: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff813d6c50)
Location: security/integrity/ima/ima_template_lib.c:33
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff813d6c50-ffffffff813d6cfe: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff813ee8f0)
Location: security/integrity/ima/ima_template_lib.c:33
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff813ee8f0-ffffffff813ee99e: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff813fad00)
Location: security/integrity/ima/ima_template_lib.c:33
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff813fad00-ffffffff813fadac: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff814231a0)
Location: security/integrity/ima/ima_template_lib.c:33
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814231a0-ffffffff8142324c: ima_write_template_field_data (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffffffff814557c0)
Location: security/integrity/ima/ima_template_lib.c:35
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814557c0-ffffffff8145586e: ima_write_template_field_data.isra.1 (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffffffff81472ba0)
Location: security/integrity/ima/ima_template_lib.c:35
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff81472ba0-ffffffff81472c4e: ima_write_template_field_data.isra.1 (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffffffff814a0890)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814a0890-ffffffff814a093f: ima_write_template_field_data.isra.0 (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffffffff814baf30)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814baf30-ffffffff814bafdf: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff8151b390)
Location: security/integrity/ima/ima_template_lib.c:29
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff8151b390-ffffffff8151b439: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81538240)
Location: security/integrity/ima/ima_template_lib.c:29
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff81538240-ffffffff815382e9: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81540950)
Location: security/integrity/ima/ima_template_lib.c:29
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff81540950-ffffffff815409fc: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0280)
Location: security/integrity/ima/ima_template_lib.c:32
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodemode_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff815a0280-ffffffff815a032c: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81645ec0)
Location: security/integrity/ima/ima_template_lib.c:45
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodemode_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff81645ec0-ffffffff81645f7d: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff816fe450)
Location: security/integrity/ima/ima_template_lib.c:45
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodemode_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff816fe450-ffffffff816fe50d: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff817383b0)
Location: security/integrity/ima/ima_template_lib.c:45
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodemode_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff817383b0-ffffffff81738477: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81778ed0)
Location: security/integrity/ima/ima_template_lib.c:45
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodemode_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff81778ed0-ffffffff81778f97: ima_write_template_field_data (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffff8000105b33f8)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffff8000105b33f8-ffff8000105b34d4: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_write_template_field_data(const void *data, const u32 datalen, enum data_formats datafmt, struct ima_field_data *field_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (c0762964)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
c0762964-c0762a1c: ima_write_template_field_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (c000000000735b60)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
c000000000735b60-c000000000735c88: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffe0003fb1d6)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffe0003fa9ea-ffffffe0003faab8: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
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
In security/integrity/ima/ima_template_lib.c (ffffffff814b3510)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814b3510-ffffffff814b35bf: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff814a3f30)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814a3f30-ffffffff814a3fdf: ima_write_template_field_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff814af5a0)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814af5a0-ffffffff814af64f: ima_write_template_field_data.isra.0 (STB_LOCAL)
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
In security/integrity/ima/ima_template_lib.c (ffffffff814c8020)
Location: security/integrity/ima/ima_template_lib.c:31
Inline: True
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventmodsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventbuf_init
  - security/integrity/ima/ima_template_lib.c:ima_eventsig_init
  - security/integrity/ima/ima_template_lib.c:ima_eventname_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init_common
```
**Symbols:**

```
ffffffff814c8020-ffffffff814c80cf: ima_write_template_field_data.isra.0 (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
