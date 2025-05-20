# Function: <code>generate_random_uuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void generate_random_uuid(unsigned char *uuid_out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513a60)
Location: drivers/char/random.c:1634
Inline: True
Inline callers:
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81513a60-ffffffff81513a94: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81441da0)
Location: lib/uuid.c:39
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff81441da0-ffffffff81441dcf: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8145efb0)
Location: lib/uuid.c:39
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff8145efb0-ffffffff8145efdf: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814642f0)
Location: lib/uuid.c:42
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff814642f0-ffffffff8146431f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81490270)
Location: lib/uuid.c:42
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff81490270-ffffffff8149029f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814c5060)
Location: lib/uuid.c:41
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff814c5060-ffffffff814c508f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814d9760)
Location: lib/uuid.c:41
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff814d9760-ffffffff814d978f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815054c0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815054c0-ffffffff815054ef: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815234a0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815234a0-ffffffff815234cf: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815869f0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815869f0-ffffffff81586a22: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815a3ce0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815a3ce0-ffffffff815a3d12: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815aabf0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815aabf0-ffffffff815aac22: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81613ea0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff81613ea0-ffffffff81613ed2: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff816e0750)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff816e0750-ffffffff816e078c: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff817d0aa0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff817d0aa0-ffffffff817d0adc: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8180f6e0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff8180f6e0-ffffffff8180f71c: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81855360)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff81855360-ffffffff8185539c: generate_random_uuid (STB_GLOBAL)
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
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffff80001062d268)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffff80001062d268-ffff80001062d2ac: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c07d3de8)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
c07d3de8-c07d3e28: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c0000000007d0260)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
c0000000007d0260-c0000000007d02c0: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffe00045d12c)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffe00045d12c-ffffffe00045d16a: generate_random_uuid (STB_GLOBAL)
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
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8151ba80)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff8151ba80-ffffffff8151baaf: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8150bd70)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff8150bd70-ffffffff8150bd9f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81517b10)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff81517b10-ffffffff81517b3f: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void generate_random_uuid(unsigned char *uuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815312b0)
Location: lib/uuid.c:33
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:proc_do_uuid
```
**Symbols:**

```
ffffffff815312b0-ffffffff815312df: generate_random_uuid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char *uuid</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char *uuid_out</code>
</li>
</ul>
</details>
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
