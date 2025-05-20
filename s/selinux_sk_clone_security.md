# Function: <code>selinux_sk_clone_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813441b0)
Location: security/selinux/hooks.c:4606
Inline: False
```
**Symbols:**

```
ffffffff813441b0-ffffffff813441e2: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81378e80)
Location: security/selinux/hooks.c:4739
Inline: False
```
**Symbols:**

```
ffffffff81378e80-ffffffff81378eb2: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138f860)
Location: security/selinux/hooks.c:4820
Inline: False
```
**Symbols:**

```
ffffffff8138f860-ffffffff8138f892: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a5d70)
Location: security/selinux/hooks.c:4798
Inline: False
```
**Symbols:**

```
ffffffff813a5d70-ffffffff813a5daf: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cb9c0)
Location: security/selinux/hooks.c:4813
Inline: False
```
**Symbols:**

```
ffffffff813cb9c0-ffffffff813cb9ff: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fa58a)
Location: security/selinux/hooks.c:5176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff813fa500-ffffffff813fa532: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81416990)
Location: security/selinux/hooks.c:4891
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff81416990-ffffffff814169cf: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814443f0)
Location: security/selinux/hooks.c:5090
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814443f0-ffffffff8144442f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145df60)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff8145df60-ffffffff8145df9f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b3ac7)
Location: security/selinux/hooks.c:5141
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814b0960-ffffffff814b099f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d0969)
Location: security/selinux/hooks.c:5157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814cdd30-ffffffff814cdd6f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6f69)
Location: security/selinux/hooks.c:5321
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814d4480-ffffffff814d44bf: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152fd75)
Location: security/selinux/hooks.c:5306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff8152d140-ffffffff8152d17f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c7b86)
Location: security/selinux/hooks.c:5210
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff815c39f0-ffffffff815c3a3d: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81674a56)
Location: security/selinux/hooks.c:5225
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff816704f0-ffffffff8167053d: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ac756)
Location: security/selinux/hooks.c:5174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff816a8b00-ffffffff816a8b4d: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e9ac6)
Location: security/selinux/hooks.c:5270
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff816e54d0-ffffffff816e551d: selinux_sk_clone_security (STB_LOCAL)
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
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054afa0)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffff80001054afa0-ffff80001054affc: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0700f2c)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
c0700f2c-c0700f7c: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a3080)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
c0000000006a3080-c0000000006a30e4: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5a06)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffe0003a5a06-ffffffe0003a5a58: selinux_sk_clone_security (STB_LOCAL)
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
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81456540)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff81456540-ffffffff8145657f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446f80)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff81446f80-ffffffff81446fbf: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814525e0)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814525e0-ffffffff8145261f: selinux_sk_clone_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selinux_sk_clone_security(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814691d0)
Location: security/selinux/hooks.c:5148
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_sk_clone
```
**Symbols:**

```
ffffffff814691d0-ffffffff8146920f: selinux_sk_clone_security (STB_LOCAL)
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
