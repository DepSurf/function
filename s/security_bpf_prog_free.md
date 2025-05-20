# Function: <code>security_bpf_prog_free</code>

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
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c75e0)
Location: security/security.c:2473
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff813c75e0-ffffffff813c761c: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6c30)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff813f6c30-ffffffff813f6c64: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814126e0)
Location: security/security.c:2546
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff814126e0-ffffffff81412714: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814400e0)
Location: security/security.c:2563
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff814400e0-ffffffff81440116: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459920)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81459920-ffffffff81459954: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aca30)
Location: security/security.c:2973
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff814aca30-ffffffff814aca64: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ca030)
Location: security/security.c:2991
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff814ca030-ffffffff814ca064: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0660)
Location: security/security.c:3054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff814d0660-ffffffff814d0694: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529390)
Location: security/security.c:3062
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff81529390-ffffffff815293c4: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bea10)
Location: security/security.c:3140
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff815bea10-ffffffff815bea4c: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166acf0)
Location: security/security.c:3120
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff8166acf0-ffffffff8166ad2c: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a3450)
Location: security/security.c:5574
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff816a3450-ffffffff816a348c: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfed0)
Location: security/security.c:5715
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff816dfed0-ffffffff816dff0c: security_bpf_prog_free (STB_GLOBAL)
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
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545b58)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffff800010545b58-ffff800010545ba0: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb9bc)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
c06fb9bc-c06fba04: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069c3f0)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
c00000000069c3f0-c00000000069c468: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1734)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffe0003a1734-ffffffe0003a176c: security_bpf_prog_free (STB_GLOBAL)
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
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451f00)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81451f00-ffffffff81451f34: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442950)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81442950-ffffffff81442984: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dfa0)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff8144dfa0-ffffffff8144dfd4: security_bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_bpf_prog_free(struct bpf_prog_aux *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465370)
Location: security/security.c:2602
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff81465370-ffffffff814653a4: security_bpf_prog_free (STB_GLOBAL)
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
