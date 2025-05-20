# Function: <code>security_sem_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_sem_free(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ee80)
Location: security/security.c:1104
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff8133ee80-ffffffff8133eeb6: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_sem_free(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813744a0)
Location: security/security.c:1128
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff813744a0-ffffffff813744d6: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_sem_free(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138add0)
Location: security/security.c:1149
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff8138add0-ffffffff8138ae06: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_sem_free(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a04c0)
Location: security/security.c:1893
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff813a04c0-ffffffff813a0509: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_sem_free(struct sem_array *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c61b0)
Location: security/security.c:1867
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff813c61b0-ffffffff813c61ff: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5e70)
Location: security/security.c:1253
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff813f5e70-ffffffff813f5ea4: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411580)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff81411580-ffffffff814115c7: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ee00)
Location: security/security.c:1914
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff8143ee00-ffffffff8143ee49: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814587c0)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff814587c0-ffffffff81458807: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab73f)
Location: security/security.c:2155
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff814ab780-ffffffff814ab7c7: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8d3f)
Location: security/security.c:2172
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff814c8d80-ffffffff814c8dc7: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf37f)
Location: security/security.c:2235
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff814cf3c0-ffffffff814cf407: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8152803f)
Location: security/security.c:2243
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff81528080-ffffffff815280c7: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd0b3)
Location: security/security.c:2254
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff815bd130-ffffffff815bd17f: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669403)
Location: security/security.c:2330
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff81669490-ffffffff816694df: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1a03)
Location: security/security.c:3924
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff816a1a90-ffffffff816a1adf: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de283)
Location: security/security.c:3953
Inline: True
Inline callers:
  - security/security.c:security_sem_alloc
Direct callers:
  - ipc/sem.c:sem_rcu_free
```
**Symbols:**

```
ffffffff816de310-ffffffff816de35f: security_sem_free (STB_GLOBAL)
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
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105446c8)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffff8000105446c8-ffff80001054471c: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa5b4)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
c06fa5b4-c06fa60c: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006995d0)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
c0000000006995d0-c00000000069965c: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a07d0)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffe0003a07d0-ffffffe0003a0818: security_sem_free (STB_GLOBAL)
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
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450da0)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff81450da0-ffffffff81450de7: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814417f0)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff814417f0-ffffffff81441837: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ce40)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff8144ce40-ffffffff8144ce87: security_sem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_sem_free(struct kern_ipc_perm *sma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464210)
Location: security/security.c:1953
Inline: False
Direct callers:
  - ipc/sem.c:sem_rcu_free
  - security/security.c:security_sem_alloc
```
**Symbols:**

```
ffffffff81464210-ffffffff81464257: security_sem_free (STB_GLOBAL)
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
