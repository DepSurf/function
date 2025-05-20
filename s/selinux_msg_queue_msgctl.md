# Function: <code>selinux_msg_queue_msgctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813463b0)
Location: security/selinux/hooks.c:5267
Inline: True
```
**Symbols:**

```
ffffffff813463b0-ffffffff813463e9: selinux_msg_queue_msgctl.part.31 (STB_LOCAL)
ffffffff813464a0-ffffffff813464e4: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137bb00)
Location: security/selinux/hooks.c:5411
Inline: True
```
**Symbols:**

```
ffffffff8137bb00-ffffffff8137bb39: selinux_msg_queue_msgctl.part.32 (STB_LOCAL)
ffffffff8137bbf0-ffffffff8137bc37: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81391f70)
Location: security/selinux/hooks.c:5492
Inline: True
```
**Symbols:**

```
ffffffff81391f70-ffffffff81391fa9: selinux_msg_queue_msgctl.part.34 (STB_LOCAL)
ffffffff81392060-ffffffff813920a7: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a8490)
Location: security/selinux/hooks.c:5421
Inline: True
```
**Symbols:**

```
ffffffff813a83a0-ffffffff813a83d9: selinux_msg_queue_msgctl.part.31 (STB_LOCAL)
ffffffff813a8490-ffffffff813a84cf: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cdc30)
Location: security/selinux/hooks.c:5436
Inline: True
```
**Symbols:**

```
ffffffff813cdb40-ffffffff813cdb79: selinux_msg_queue_msgctl.part.32 (STB_LOCAL)
ffffffff813cdc30-ffffffff813cdc75: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb290)
Location: security/selinux/hooks.c:6027
Inline: True
```
**Symbols:**

```
ffffffff813fb170-ffffffff813fb1b1: selinux_msg_queue_msgctl.part.42 (STB_LOCAL)
ffffffff813fb290-ffffffff813fb2dd: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81417770)
Location: security/selinux/hooks.c:5702
Inline: True
```
**Symbols:**

```
ffffffff81417620-ffffffff81417661: selinux_msg_queue_msgctl.part.39 (STB_LOCAL)
ffffffff81417770-ffffffff814177c1: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445370)
Location: security/selinux/hooks.c:5901
Inline: True
```
**Symbols:**

```
ffffffff81445370-ffffffff814453f7: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145eef0)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffff8145eef0-ffffffff8145ef7f: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b1c10)
Location: security/selinux/hooks.c:5962
Inline: True
```
**Symbols:**

```
ffffffff814b1c10-ffffffff814b1c9f: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf010)
Location: security/selinux/hooks.c:5978
Inline: True
```
**Symbols:**

```
ffffffff814cf010-ffffffff814cf09f: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5810)
Location: security/selinux/hooks.c:6142
Inline: True
```
**Symbols:**

```
ffffffff814d5810-ffffffff814d58a0: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152e3d0)
Location: security/selinux/hooks.c:6127
Inline: True
```
**Symbols:**

```
ffffffff8152e3d0-ffffffff8152e460: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c52e0)
Location: security/selinux/hooks.c:6026
Inline: True
```
**Symbols:**

```
ffffffff815c52e0-ffffffff815c53ae: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81671ea0)
Location: security/selinux/hooks.c:6039
Inline: True
```
**Symbols:**

```
ffffffff81671ea0-ffffffff81671f6e: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816aa3f0)
Location: security/selinux/hooks.c:5989
Inline: True
```
**Symbols:**

```
ffffffff816aa3f0-ffffffff816aa4b3: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e7250)
Location: security/selinux/hooks.c:6074
Inline: True
```
**Symbols:**

```
ffffffff816e7250-ffffffff816e7316: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffff80001054bff8)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffff80001054be08-ffff80001054be5c: selinux_msg_queue_msgctl.part.0 (STB_LOCAL)
ffff80001054bff8-ffff80001054c090: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (c07022f0)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
c0702124-c070218c: selinux_msg_queue_msgctl.part.0 (STB_LOCAL)
c07022f0-c0702378: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4890)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
c0000000006a4890-c0000000006a4998: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a674a)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffe0003a6606-ffffffe0003a664a: selinux_msg_queue_msgctl.part.0 (STB_LOCAL)
ffffffe0003a674a-ffffffe0003a67c0: selinux_msg_queue_msgctl (STB_LOCAL)
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
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814574d0)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffff814574d0-ffffffff8145755f: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81447f00)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffff81447f00-ffffffff81447f8f: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81453570)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffff81453570-ffffffff814535ff: selinux_msg_queue_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146b0f0)
Location: security/selinux/hooks.c:5959
Inline: True
```
**Symbols:**

```
ffffffff8146b0f0-ffffffff8146b17f: selinux_msg_queue_msgctl (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct msg_queue *msq</code> ➡️ <code>struct kern_ipc_perm *msq</code>
</li>
</ul>
</details>
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
