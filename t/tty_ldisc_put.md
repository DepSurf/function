# Function: <code>tty_ldisc_put</code>

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
In drivers/tty/tty_ldisc.c (ffffffff814e9b1c)
Location: drivers/tty/tty_ldisc.c:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153ab20)
Location: drivers/tty/tty_ldisc.c:195
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8153ab20-ffffffff8153ab76: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815671e0)
Location: drivers/tty/tty_ldisc.c:195
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff815671e0-ffffffff81567236: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157a830)
Location: drivers/tty/tty_ldisc.c:195
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8157a830-ffffffff8157a866: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df1d0)
Location: drivers/tty/tty_ldisc.c:196
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff815df1d0-ffffffff815df208: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816184f0)
Location: drivers/tty/tty_ldisc.c:195
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff816184f0-ffffffff81618527: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816356c0)
Location: drivers/tty/tty_ldisc.c:195
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff816356c0-ffffffff816356f7: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669790)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff81669790-ffffffff816697c8: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168bf20)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8168bf20-ffffffff8168bf58: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e0a0)
Location: drivers/tty/tty_ldisc.c:199
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8173e0a0-ffffffff8173e0fc: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a000)
Location: drivers/tty/tty_ldisc.c:198
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8175a000-ffffffff8175a05c: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173ddd0)
Location: drivers/tty/tty_ldisc.c:199
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8173ddd0-ffffffff8173de2c: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817be2c0)
Location: drivers/tty/tty_ldisc.c:184
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff817be2c0-ffffffff817be315: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818fa640)
Location: drivers/tty/tty_ldisc.c:179
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff818fa640-ffffffff818fa6a9: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a53780)
Location: drivers/tty/tty_ldisc.c:179
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff81a53780-ffffffff81a537e9: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9eadc)
Location: drivers/tty/tty_ldisc.c:178
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af15fc)
Location: drivers/tty/tty_ldisc.c:178
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
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
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085c368)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffff80001085c368-ffff80001085c3b8: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0964468)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
c0964468-c09644cc: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fb070)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
c0000000008fb070-c0000000008fb0e0: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe0005355dc)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffe0005355dc-ffffffe000535626: tty_ldisc_put (STB_LOCAL)
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
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816519a0)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff816519a0-ffffffff816519d8: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81631de0)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff81631de0-ffffffff81631e18: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8167fd60)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8167fd60-ffffffff8167fd98: tty_ldisc_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc *ld);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169a3b0)
Location: drivers/tty/tty_ldisc.c:204
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_deinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_reinit
  - drivers/tty/tty_ldisc.c:tty_ldisc_kill
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_failto
```
**Symbols:**

```
ffffffff8169a3b0-ffffffff8169a3e8: tty_ldisc_put (STB_LOCAL)
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
