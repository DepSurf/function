# Function: <code>security_sem_semctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ef10)
Location: security/security.c:1114
Inline: False
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff8133ef10-ffffffff8133ef5f: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374530)
Location: security/security.c:1138
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81374530-ffffffff8137457f: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ae60)
Location: security/security.c:1159
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8138ae60-ffffffff8138aeaf: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0560)
Location: security/security.c:1907
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff813a0560-ffffffff813a05af: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6300)
Location: security/security.c:1881
Inline: False
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff813c6300-ffffffff813c6355: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5f00)
Location: security/security.c:1263
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff813f5f00-ffffffff813f5f44: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814116b0)
Location: security/security.c:1907
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff814116b0-ffffffff814116f4: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ef30)
Location: security/security.c:1926
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff8143ef30-ffffffff8143ef7d: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814588f0)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff814588f0-ffffffff81458934: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab820)
Location: security/security.c:2167
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff814ab820-ffffffff814ab864: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8e20)
Location: security/security.c:2184
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff814c8e20-ffffffff814c8e64: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf460)
Location: security/security.c:2247
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff814cf460-ffffffff814cf4a4: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528120)
Location: security/security.c:2255
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff81528120-ffffffff81528164: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd1e0)
Location: security/security.c:2266
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff815bd1e0-ffffffff815bd23d: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669560)
Location: security/security.c:2342
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff81669560-ffffffff816695bd: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1b60)
Location: security/security.c:3957
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff816a1b60-ffffffff816a1bbd: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de3e0)
Location: security/security.c:3986
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff816de3e0-ffffffff816de43d: security_sem_semctl (STB_GLOBAL)
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
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544818)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffff800010544818-ffff800010544878: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa6fc)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c06fa6fc-c06fa758: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699820)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
c000000000699820-c0000000006998dc: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a08da)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffe0003a08da-ffffffe0003a091e: security_sem_semctl (STB_GLOBAL)
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
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450ed0)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff81450ed0-ffffffff81450f14: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441920)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff81441920-ffffffff81441964: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cf70)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff8144cf70-ffffffff8144cfb4: security_sem_semctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sem_semctl(struct kern_ipc_perm *sma, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464340)
Location: security/security.c:1965
Inline: False
Direct callers:
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
```
**Symbols:**

```
ffffffff81464340-ffffffff81464384: security_sem_semctl (STB_GLOBAL)
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
