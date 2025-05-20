# Function: <code>wait_for_tpm_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523690)
Location: drivers/char/tpm/tpm-interface.c:876
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:recv_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81523690-ffffffff815238ac: wait_for_tpm_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815765d0)
Location: drivers/char/tpm/tpm-interface.c:904
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff815765d0-ffffffff815767eb: wait_for_tpm_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2c60)
Location: drivers/char/tpm/tpm-interface.c:889
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff815a2c60-ffffffff815a2e52: wait_for_tpm_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b67e0)
Location: drivers/char/tpm/tpm-interface.c:1053
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff815b67e0-ffffffff815b69b9: wait_for_tpm_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d500)
Location: drivers/char/tpm/tpm-interface.c:1071
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8161d500-ffffffff8161d6e6: wait_for_tpm_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165df60)
Location: drivers/char/tpm/tpm_tis_core.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8165df60-ffffffff8165e143: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c420)
Location: drivers/char/tpm/tpm_tis_core.c:51
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8167c420-ffffffff8167c603: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b32c0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff816b32c0-ffffffff816b34b4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5fa0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff816d5fa0-ffffffff816d6194: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a4e0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8178a4e0-ffffffff8178a6d4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a1460)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff817a1460-ffffffff817a1654: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783ff0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff81783ff0-ffffffff817841e4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8180aa30-ffffffff8180ac40: wait_for_tpm_stat (STB_LOCAL)
ffffffff81cfd3ae-ffffffff81cfd3c2: wait_for_tpm_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8194a500-ffffffff8194a743: wait_for_tpm_stat (STB_LOCAL)
ffffffff81ec5a0b-ffffffff81ec5a1f: wait_for_tpm_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff81aadba0-ffffffff81aadddd: wait_for_tpm_stat (STB_LOCAL)
ffffffff82096bb3-ffffffff82096bc7: wait_for_tpm_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:64
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff81af9510-ffffffff81af981d: wait_for_tpm_stat (STB_LOCAL)
ffffffff82117ae0-ffffffff82117af5: wait_for_tpm_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:64
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff81b4cb30-ffffffff81b4ce3d: wait_for_tpm_stat (STB_LOCAL)
ffffffff821f5855-ffffffff821f586a: wait_for_tpm_stat.cold (STB_LOCAL)
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
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c12e0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffff8000108c12e0-ffff8000108c1508: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b978c)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
c09b978c-c09b99a8: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000963070)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
c000000000963070-c0000000009633a4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572642)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffe000572642-ffffffe0005727d6: wait_for_tpm_stat (STB_LOCAL)
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
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b9f0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff8169b9f0-ffffffff8169bbe4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816793e0)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff816793e0-ffffffff816795d4: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9c60)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff816c9c60-ffffffff816c9e54: wait_for_tpm_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip *chip, u8 mask, long unsigned int timeout, wait_queue_head_t *queue, bool check_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4140)
Location: drivers/char/tpm/tpm_tis_core.c:47
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:recv_data
```
**Symbols:**

```
ffffffff816e4140-ffffffff816e432f: wait_for_tpm_stat (STB_LOCAL)
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
