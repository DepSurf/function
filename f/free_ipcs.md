# Function: <code>free_ipcs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8132ea90)
Location: ipc/namespace.c:70
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8132ea90-ffffffff8132eb49: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81363750)
Location: ipc/namespace.c:70
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff81363750-ffffffff81363809: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81379f60)
Location: ipc/namespace.c:92
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff81379f60-ffffffff8137a01c: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8138db60)
Location: ipc/namespace.c:94
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8138db60-ffffffff8138dbf0: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813b2fd0)
Location: ipc/namespace.c:107
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff813b2fd0-ffffffff813b3062: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813e3710)
Location: ipc/namespace.c:107
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff813e3710-ffffffff813e37a2: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813fe050)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff813fe050-ffffffff813fe0e2: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8142a680)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8142a680-ffffffff8142a712: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff814443b0)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff814443b0-ffffffff81444442: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff814953a0)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff814953a0-ffffffff81495432: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff814b2e00)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff814b2e00-ffffffff814b2e92: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff814b8c40)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff814b8c40-ffffffff814b8cd2: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81511470)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff81511470-ffffffff81511502: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff815a36f0)
Location: ipc/namespace.c:105
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff815a36f0-ffffffff815a3794: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8164d330)
Location: ipc/namespace.c:108
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8164d330-ffffffff8164d3d4: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81685ad0)
Location: ipc/namespace.c:123
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff81685ad0-ffffffff81685b73: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff816c1ef0)
Location: ipc/namespace.c:123
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff816c1ef0-ffffffff816c1f93: free_ipcs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffff80001052cdf0)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffff80001052cdf0-ffff80001052ced4: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (c06e56d4)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
c06e56d4-c06e5764: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (c000000000678e60)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
c000000000678e60-c000000000678f6c: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffe00038eca0)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffe00038eca0-ffffffe00038ed2e: free_ipcs (STB_GLOBAL)
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
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8143c990)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8143c990-ffffffff8143ca22: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8142d400)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8142d400-ffffffff8142d492: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81438b30)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff81438b30-ffffffff81438bc2: free_ipcs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_ipcs(struct ipc_namespace *ns, struct ipc_ids *ids, void (*free)(struct ipc_namespace *, struct kern_ipc_perm *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8144fca0)
Location: ipc/namespace.c:95
Inline: False
Direct callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
```
**Symbols:**

```
ffffffff8144fca0-ffffffff8144fd38: free_ipcs (STB_GLOBAL)
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
