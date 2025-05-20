# Function: <code>msg_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8125acc5)
Location: fs/userfaultfd.c:145
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff81f97d03)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff81f97d03-ffffffff81f97d66: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81283876)
Location: fs/userfaultfd.c:145
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff81fc2902)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff81fc2902-ffffffff81fc2965: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81297391)
Location: fs/userfaultfd.c:152
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff81fff31c)
Location: ipc/msg.c:1060
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff81fff31c-ffffffff81fff37f: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a5663)
Location: fs/userfaultfd.c:172
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff820e25e6)
Location: ipc/msg.c:1061
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff820e25e6-ffffffff820e264b: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c8b73)
Location: fs/userfaultfd.c:169
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff826eb27b)
Location: ipc/msg.c:1207
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff826eb27b-ffffffff826eb2e6: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1e93)
Location: fs/userfaultfd.c:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff82715774)
Location: ipc/msg.c:1280
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff82715774-ffffffff827157df: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81306853)
Location: fs/userfaultfd.c:170
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828ccbe3)
Location: ipc/msg.c:1290
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828ccbe3-ffffffff828ccc48: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81327df3)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828e656d)
Location: ipc/msg.c:1315
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828e656d-ffffffff828e65d2: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133abd3)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828ef026)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828ef026-ffffffff828ef08b: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374cd1)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff82d04315)
Location: ipc/msg.c:1347
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff82d04315-ffffffff82d0437a: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81382ba1)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff82ff16e2)
Location: ipc/msg.c:1347
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff82ff16e2-ffffffff82ff1747: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81389c11)
Location: fs/userfaultfd.c:181
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff831fbf92)
Location: ipc/msg.c:1349
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff831fbf92-ffffffff831fbff7: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6ef1)
Location: fs/userfaultfd.c:182
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff832e2fe4)
Location: ipc/msg.c:1349
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff832e2fe4-ffffffff832e3049: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (ffffffff8146088b)
Location: fs/userfaultfd.c:184
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff834992ce)
Location: ipc/msg.c:1349
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff81e78061-ffffffff81e78071: msg_init.part.0 (STB_LOCAL)
ffffffff834992ce-ffffffff8349933b: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f07ab)
Location: fs/userfaultfd.c:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff83ecf260)
Location: ipc/msg.c:1369
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff814ed370-ffffffff814ed380: msg_init.part.0 (STB_LOCAL)
ffffffff83ecf260-ffffffff83ecf2a4: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8152758b)
Location: fs/userfaultfd.c:230
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff836f42d0)
Location: ipc/msg.c:1369
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff836f42d0-ffffffff836f4314: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155c38b)
Location: fs/userfaultfd.c:234
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff839274e0)
Location: ipc/msg.c:1369
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff839274e0-ffffffff83927524: msg_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f9cc0)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffff800011468c74)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffff800011468c74-ffff800011468cdc: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cdb94)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (c1541774)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
c1541774-c15417e0: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000502510)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (c000000001396ba4)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
c000000001396ba4-c000000001396c2c: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8e86)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffe000023eac)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffe000023eac-ffffffe000023f1a: msg_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813331b3)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828d7eda)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828d7eda-ffffffff828d7f3f: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323d03)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828d05f6)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828d05f6-ffffffff828d065b: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330c83)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828eac5a)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828eac5a-ffffffff828eacbf: msg_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void msg_init(struct uffd_msg *msg);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813435d3)
Location: fs/userfaultfd.c:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_complete
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_complete
  - fs/userfaultfd.c:dup_userfaultfd_complete
  - fs/userfaultfd.c:handle_userfault
```
```
In ipc/msg.c (ffffffff828f0070)
Location: ipc/msg.c:1316
Inline: False
Direct callers:
  - ipc/util.c:ipc_init
```
**Symbols:**

```
ffffffff828f0070-ffffffff828f00d5: msg_init (STB_GLOBAL)
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
