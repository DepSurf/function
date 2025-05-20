# Function: <code>audit_put_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112aaa7)
Location: kernel/audit.c:1898
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8112b990-ffffffff8112b9a0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811347c7)
Location: kernel/audit.c:2037
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811356b0-ffffffff811356c0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135c1f)
Location: kernel/audit.c:2204
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81136c60-ffffffff81136c70: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114295f)
Location: kernel/audit.c:2212
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81143960-ffffffff81143970: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115133f)
Location: kernel/audit.c:2265
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811523b0-ffffffff811523c0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115dff1)
Location: kernel/audit.c:2263
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8115f060-ffffffff8115f070: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b627)
Location: kernel/audit.c:2116
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116b3e0-ffffffff8116b3f0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81177507)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811772c0-ffffffff811772d0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81189fdb)
Location: kernel/audit.c:2267
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff8118a010-ffffffff8118a020: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811872e6)
Location: kernel/audit.c:2284
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81187320-ffffffff81187330: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811884e2)
Location: kernel/audit.c:2284
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81188250-ffffffff81188260: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0a02)
Location: kernel/audit.c:2323
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff811b0770-ffffffff811b0780: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2c07)
Location: kernel/audit.c:2369
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff811e2920-ffffffff811e2936: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228ae7)
Location: kernel/audit.c:2367
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff812287e0-ffffffff812287f6: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123f0e7)
Location: kernel/audit.c:2367
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff8123ede0-ffffffff8123edf6: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258f5f)
Location: kernel/audit.c:2389
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
```
**Symbols:**

```
ffffffff81258c60-ffffffff81258c76: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec458)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffff8000101ec258-ffff8000101ec284: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042c144)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c042be78-c042be94: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025def0)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
c00000000025dbc0-c00000000025dbf4: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe000160ba6)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffe000160988-ffffffe0001609b2: audit_put_tty (STB_GLOBAL)
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
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116fb27)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116f8e0-ffffffff8116f8f0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162cc7)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81162a80-ffffffff81162a90: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d8f7)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8116d6b0-ffffffff8116d6c0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_put_tty(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117b0f0)
Location: kernel/audit.c:2118
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff8117aea0-ffffffff8117aeb0: audit_put_tty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
