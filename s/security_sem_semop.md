# Function: <code>security_sem_semop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ef60)
Location: security/security.c:1119
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff8133ef60-ffffffff8133efc7: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374580)
Location: security/security.c:1143
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81374580-ffffffff813745e7: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138aeb0)
Location: security/security.c:1164
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff8138aeb0-ffffffff8138af17: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a05b0)
Location: security/security.c:1912
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff813a05b0-ffffffff813a0617: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6360)
Location: security/security.c:1886
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff813c6360-ffffffff813c63cd: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5f50)
Location: security/security.c:1268
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff813f5f50-ffffffff813f5fa8: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411700)
Location: security/security.c:1912
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81411700-ffffffff81411758: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ef80)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8143ef80-ffffffff8143efe3: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458940)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81458940-ffffffff81458996: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab870)
Location: security/security.c:2172
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814ab870-ffffffff814ab8c6: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8e70)
Location: security/security.c:2189
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814c8e70-ffffffff814c8ec6: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf4b0)
Location: security/security.c:2252
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814cf4b0-ffffffff814cf506: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528170)
Location: security/security.c:2260
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81528170-ffffffff815281c6: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd240)
Location: security/security.c:2271
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff815bd240-ffffffff815bd2bb: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816695d0)
Location: security/security.c:2347
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816695d0-ffffffff8166964b: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1bd0)
Location: security/security.c:3974
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816a1bd0-ffffffff816a1c4b: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de450)
Location: security/security.c:4003
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816de450-ffffffff816de4cb: security_sem_semop (STB_GLOBAL)
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
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544878)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffff800010544878-ffff8000105448ec: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa758)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c06fa758-c06fa7c4: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006998e0)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c0000000006998e0-c0000000006999c4: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a091e)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffe0003a091e-ffffffe0003a0972: security_sem_semop (STB_GLOBAL)
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
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450f20)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81450f20-ffffffff81450f76: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441970)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81441970-ffffffff814419c6: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cfc0)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8144cfc0-ffffffff8144d016: security_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm *sma, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464390)
Location: security/security.c:1970
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81464390-ffffffff814643e6: security_sem_semop (STB_GLOBAL)
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
