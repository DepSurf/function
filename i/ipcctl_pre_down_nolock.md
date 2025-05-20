# Function: <code>ipcctl_pre_down_nolock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81325260)
Location: ipc/util.c:687
Inline: False
```
**Symbols:**

```
ffffffff81325260-ffffffff81325354: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359e40)
Location: ipc/util.c:682
Inline: False
```
**Symbols:**

```
ffffffff81359e40-ffffffff81359f33: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81370320)
Location: ipc/util.c:682
Inline: False
```
**Symbols:**

```
ffffffff81370320-ffffffff81370413: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813836f0)
Location: ipc/util.c:628
Inline: False
```
**Symbols:**

```
ffffffff813836f0-ffffffff813837e5: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a7b60)
Location: ipc/util.c:694
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff813a7b60-ffffffff813a7c55: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_pre_down_nolock(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6f40)
Location: ipc/util.c:698
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff813d6f40-ffffffff813d7031: ipcctl_pre_down_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
