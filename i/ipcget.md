# Function: <code>ipcget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81325020)
Location: ipc/util.c:640
Inline: False
Direct callers:
  - ipc/msg.c:SyS_msgget
  - ipc/sem.c:SyS_semget
  - ipc/shm.c:SyS_shmget
```
**Symbols:**

```
ffffffff81325020-ffffffff813251cd: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359c10)
Location: ipc/util.c:635
Inline: False
Direct callers:
  - ipc/msg.c:SyS_msgget
  - ipc/sem.c:SyS_semget
  - ipc/shm.c:SyS_shmget
```
**Symbols:**

```
ffffffff81359c10-ffffffff81359daa: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813700f0)
Location: ipc/util.c:635
Inline: False
Direct callers:
  - ipc/msg.c:SyS_msgget
  - ipc/sem.c:SyS_semget
  - ipc/shm.c:SyS_shmget
```
**Symbols:**

```
ffffffff813700f0-ffffffff8137028d: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813834e0)
Location: ipc/util.c:579
Inline: False
Direct callers:
  - ipc/msg.c:SyS_msgget
  - ipc/sem.c:SyS_semget
  - ipc/shm.c:SyS_shmget
```
**Symbols:**

```
ffffffff813834e0-ffffffff8138365f: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a78a0)
Location: ipc/util.c:645
Inline: False
Direct callers:
  - ipc/msg.c:SyS_msgget
  - ipc/sem.c:SyS_semget
  - ipc/shm.c:SyS_shmget
```
**Symbols:**

```
ffffffff813a78a0-ffffffff813a7ac7: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6c40)
Location: ipc/util.c:649
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff813d6c40-ffffffff813d6ea9: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f1240)
Location: ipc/util.c:610
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff813f1240-ffffffff813f14bd: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d4e0)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff8141d4e0-ffffffff8141d772: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81437330)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81437330-ffffffff814375c2: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487480)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81487480-ffffffff814875c1: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4aa0)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff814a4aa0-ffffffff814a4be6: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aaa60)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff814aaa60-ffffffff814aaba6: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81502f50)
Location: ipc/util.c:673
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81502f50-ffffffff81503096: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81594590)
Location: ipc/util.c:673
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81594590-ffffffff815946de: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163d1f0)
Location: ipc/util.c:673
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff8163d1f0-ffffffff8163d33e: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81675700)
Location: ipc/util.c:673
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81675700-ffffffff81675852: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1ac0)
Location: ipc/util.c:673
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:__ia32_sys_semget
  - ipc/sem.c:__x64_sys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff816b1ac0-ffffffff816b1c12: ipcget (STB_GLOBAL)
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
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051db18)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__arm64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__arm64_sys_shmget
```
**Symbols:**

```
ffff80001051db18-ffff80001051ddec: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9f68)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:ksys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:ksys_shmget
```
**Symbols:**

```
c06d9f68-c06da258: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666e90)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__se_sys_shmget
```
**Symbols:**

```
c000000000666e90-c000000000667238: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe000385356)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__se_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__se_sys_shmget
```
**Symbols:**

```
ffffffe000385356-ffffffe0003855c6: ipcget (STB_GLOBAL)
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
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f910)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff8142f910-ffffffff8142fba2: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81420390)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81420390-ffffffff81420622: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142bab0)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff8142bab0-ffffffff8142bd42: ipcget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace *ns, struct ipc_ids *ids, const struct ipc_ops *ops, struct ipc_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442ac0)
Location: ipc/util.c:639
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_sys_msgget
  - ipc/msg.c:__x64_sys_msgget
  - ipc/sem.c:ksys_semget
  - ipc/shm.c:__ia32_sys_shmget
  - ipc/shm.c:__x64_sys_shmget
```
**Symbols:**

```
ffffffff81442ac0-ffffffff81442d67: ipcget (STB_GLOBAL)
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
