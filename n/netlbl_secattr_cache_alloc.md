# Function: <code>netlbl_secattr_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8135a83c)
Location: include/net/netlabel.h:232
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813907f7)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a7417)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bddf7)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e3f97)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81414791)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81430d75)
Location: include/net/netlabel.h:292
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145e78e)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147853e)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cda07)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eb06d)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814f4a09)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1d66)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814fb979)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154c443)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815565e9)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e52d3)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815f09cc)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81694723)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816a0dfc)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816ccc16)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816d973c)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817091ff)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff81716186)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010568618)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071c8bc)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006cbc78)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bde24)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81470b1e)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146153e)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146cbbe)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814843dd)
Location: include/net/netlabel.h:278
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
</details>
</li>
</ul>

## Differences
