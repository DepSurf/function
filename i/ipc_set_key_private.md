# Function: <code>ipc_set_key_private</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a74c0)
Location: ipc/util.c:455
Inline: False
```
**Symbols:**

```
ffffffff813a74c0-ffffffff813a74e3: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6730)
Location: ipc/util.c:459
Inline: False
```
**Symbols:**

```
ffffffff813d6730-ffffffff813d6889: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f0dc0)
Location: ipc/util.c:459
Inline: False
```
**Symbols:**

```
ffffffff813f0dc0-ffffffff813f0f16: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d1c0)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff8141d1c0-ffffffff8141d1ed: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81437010)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff81437010-ffffffff8143703d: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487110)
Location: ipc/util.c:488
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81487110-ffffffff81487143: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4730)
Location: ipc/util.c:488
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814a4730-ffffffff814a4763: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aa700)
Location: ipc/util.c:488
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814aa700-ffffffff814aa733: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502bc0)
Location: ipc/util.c:522
Inline: False
```
**Symbols:**

```
ffffffff81502bc0-ffffffff81502bf3: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81594170)
Location: ipc/util.c:522
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81594170-ffffffff815941b7: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163cd50)
Location: ipc/util.c:522
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8163cd50-ffffffff8163cd97: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81675260)
Location: ipc/util.c:522
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81675260-ffffffff816752a7: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1620)
Location: ipc/util.c:522
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff816b1620-ffffffff816b1667: ipc_set_key_private (STB_GLOBAL)
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
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051d778)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffff80001051d778-ffff80001051d7c8: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9bcc)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
c06d9bcc-c06d9c04: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c0000000006669d0)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
c0000000006669d0-c000000000666a38: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe000384ffa)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffe000384ffa-ffffffe000385044: ipc_set_key_private (STB_GLOBAL)
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
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f5f0)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff8142f5f0-ffffffff8142f61d: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81420070)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff81420070-ffffffff8142009d: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142b790)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff8142b790-ffffffff8142b7bd: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipc_set_key_private(struct ipc_ids *ids, struct kern_ipc_perm *ipcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814427a0)
Location: ipc/util.c:488
Inline: False
```
**Symbols:**

```
ffffffff814427a0-ffffffff814427cd: ipc_set_key_private (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
