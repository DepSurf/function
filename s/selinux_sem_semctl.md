# Function: <code>selinux_sem_semctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81346440)
Location: security/selinux/hooks.c:5501
Inline: True
```
**Symbols:**

```
ffffffff813463b0-ffffffff813463e9: selinux_sem_semctl.part.29 (STB_LOCAL)
ffffffff81346440-ffffffff81346499: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137bb90)
Location: security/selinux/hooks.c:5645
Inline: True
```
**Symbols:**

```
ffffffff8137bb00-ffffffff8137bb39: selinux_sem_semctl.part.30 (STB_LOCAL)
ffffffff8137bb90-ffffffff8137bbec: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81392000)
Location: security/selinux/hooks.c:5726
Inline: True
```
**Symbols:**

```
ffffffff81391f70-ffffffff81391fa9: selinux_sem_semctl.part.32 (STB_LOCAL)
ffffffff81392000-ffffffff8139205c: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a83a0)
Location: security/selinux/hooks.c:5633
Inline: True
```
**Symbols:**

```
ffffffff813a83a0-ffffffff813a83d9: selinux_sem_semctl.part.29 (STB_LOCAL)
ffffffff813a83e0-ffffffff813a8434: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cdb40)
Location: security/selinux/hooks.c:5648
Inline: True
```
**Symbols:**

```
ffffffff813cdb40-ffffffff813cdb79: selinux_sem_semctl.part.30 (STB_LOCAL)
ffffffff813cdb80-ffffffff813cdbda: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb170)
Location: security/selinux/hooks.c:6276
Inline: True
```
**Symbols:**

```
ffffffff813fb170-ffffffff813fb1b1: selinux_sem_semctl.part.40 (STB_LOCAL)
ffffffff813fb1c0-ffffffff813fb222: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81417620)
Location: security/selinux/hooks.c:5927
Inline: True
```
**Symbols:**

```
ffffffff81417620-ffffffff81417661: selinux_sem_semctl.part.37 (STB_LOCAL)
ffffffff81417670-ffffffff814176fc: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445200)
Location: security/selinux/hooks.c:6126
Inline: True
```
**Symbols:**

```
ffffffff81445200-ffffffff814452c1: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145ed70)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffff8145ed70-ffffffff8145ee39: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814af870)
Location: security/selinux/hooks.c:6187
Inline: False
```
**Symbols:**

```
ffffffff814af870-ffffffff814af939: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cd310)
Location: security/selinux/hooks.c:6203
Inline: False
```
**Symbols:**

```
ffffffff814cd310-ffffffff814cd3d9: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d3910)
Location: security/selinux/hooks.c:6367
Inline: False
```
**Symbols:**

```
ffffffff814d3910-ffffffff814d39d9: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152c5d0)
Location: security/selinux/hooks.c:6352
Inline: False
```
**Symbols:**

```
ffffffff8152c5d0-ffffffff8152c699: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c2770)
Location: security/selinux/hooks.c:6251
Inline: False
```
**Symbols:**

```
ffffffff815c2770-ffffffff815c2873: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166ef90)
Location: security/selinux/hooks.c:6260
Inline: False
```
**Symbols:**

```
ffffffff8166ef90-ffffffff8166f093: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a75a0)
Location: security/selinux/hooks.c:6199
Inline: False
```
**Symbols:**

```
ffffffff816a75a0-ffffffff816a769a: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e3ff0)
Location: security/selinux/hooks.c:6280
Inline: False
```
**Symbols:**

```
ffffffff816e3ff0-ffffffff816e40ed: selinux_sem_semctl (STB_LOCAL)
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
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffff80001054be08)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffff80001054be08-ffff80001054be5c: selinux_sem_semctl.part.0 (STB_LOCAL)
ffff80001054be60-ffff80001054bf48: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (c0702124)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
c0702124-c070218c: selinux_sem_semctl.part.0 (STB_LOCAL)
c070218c-c0702254: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4600)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
c0000000006a4600-c0000000006a4758: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a6606)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffe0003a6606-ffffffe0003a664a: selinux_sem_semctl.part.0 (STB_LOCAL)
ffffffe0003a664a-ffffffe0003a66ce: selinux_sem_semctl (STB_LOCAL)
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
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457350)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffff81457350-ffffffff81457419: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81447d80)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffff81447d80-ffffffff81447e49: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814533f0)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffff814533f0-ffffffff814534b9: selinux_sem_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146af70)
Location: security/selinux/hooks.c:6184
Inline: True
```
**Symbols:**

```
ffffffff8146af70-ffffffff8146b039: selinux_sem_semctl (STB_LOCAL)
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
<code>struct sem_array *sma</code> ➡️ <code>struct kern_ipc_perm *sma</code>
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
