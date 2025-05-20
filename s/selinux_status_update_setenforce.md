# Function: <code>selinux_status_update_setenforce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff8135cb60)
Location: security/selinux/ss/status.c:83
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8135cb60-ffffffff8135cbc0: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81392b30)
Location: security/selinux/ss/status.c:83
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81392b30-ffffffff81392b8a: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff813a9750)
Location: security/selinux/ss/status.c:83
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff813a9750-ffffffff813a97a4: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff813c0110)
Location: security/selinux/ss/status.c:83
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff813c0110-ffffffff813c0164: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff813e62b0)
Location: security/selinux/ss/status.c:83
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff813e62b0-ffffffff813e6304: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81416fc0)
Location: security/selinux/ss/status.c:82
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81416fc0-ffffffff81417029: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff814334d0)
Location: security/selinux/ss/status.c:82
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814334d0-ffffffff81433539: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81460ef0)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81460ef0-ffffffff81460f59: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff8147aca0)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8147aca0-ffffffff8147ad09: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff814be500)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814be500-ffffffff814be559: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff814dbf20)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814dbf20-ffffffff814dbf79: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff814e2880)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814e2880-ffffffff814e28d9: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff8153ba40)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8153ba40-ffffffff8153ba99: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff815d3290)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff815d3290-ffffffff815d32f3: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff816812b0)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff816812b0-ffffffff81681313: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void selinux_status_update_setenforce(int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff816b9360)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff816b9360-ffffffff816b93bf: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void selinux_status_update_setenforce(bool enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/status.c (ffffffff816f5e10)
Location: security/selinux/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff816f5e10-ffffffff816f5e72: selinux_status_update_setenforce (STB_GLOBAL)
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
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffff80001056b2e8)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffff80001056b2e8-ffff80001056b370: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (c071ee10)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
c071ee10-c071ee80: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (c0000000006cf220)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
c0000000006cf220-c0000000006cf2d4: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffe0003c007e)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffe0003c007e-ffffffe0003c017c: selinux_status_update_setenforce (STB_GLOBAL)
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
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81473280)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81473280-ffffffff814732e9: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81463ca0)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81463ca0-ffffffff81463d09: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff8146f320)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8146f320-ffffffff8146f389: selinux_status_update_setenforce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selinux_status_update_setenforce(struct selinux_state *state, int enforcing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/status.c (ffffffff81486b90)
Location: security/selinux/ss/status.c:79
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81486b90-ffffffff81486bf9: selinux_status_update_setenforce (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>enforcing</code> ➡️ <code>state, enforcing</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, enforcing</code> ➡️ <code>enforcing</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int enforcing</code> ➡️ <code>bool enforcing</code>
</li>
</ul>
</details>
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
