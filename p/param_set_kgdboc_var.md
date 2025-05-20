# Function: <code>param_set_kgdboc_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81510da0)
Location: drivers/tty/serial/kgdboc.c:248
Inline: False
```
**Symbols:**

```
ffffffff81510da0-ffffffff81510e66: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81563320)
Location: drivers/tty/serial/kgdboc.c:248
Inline: False
```
**Symbols:**

```
ffffffff81563320-ffffffff815633e6: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff8158fa90)
Location: drivers/tty/serial/kgdboc.c:248
Inline: False
```
**Symbols:**

```
ffffffff8158fa90-ffffffff8158fb56: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff815a3b40)
Location: drivers/tty/serial/kgdboc.c:248
Inline: False
```
**Symbols:**

```
ffffffff815a3b40-ffffffff815a3c2b: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81609280)
Location: drivers/tty/serial/kgdboc.c:245
Inline: False
```
**Symbols:**

```
ffffffff81609280-ffffffff8160936b: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:245
Inline: False
```
**Symbols:**

```
ffffffff816429c0-ffffffff81642a7f: param_set_kgdboc_var (STB_LOCAL)
ffffffff81642a95-ffffffff81642acd: param_set_kgdboc_var.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff81660b00-ffffffff81660c6b: param_set_kgdboc_var (STB_LOCAL)
ffffffff81660c97-ffffffff81660cc3: param_set_kgdboc_var.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff816966c0-ffffffff8169682e: param_set_kgdboc_var (STB_LOCAL)
ffffffff8169685a-ffffffff81696886: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff816b9250-ffffffff816b93be: param_set_kgdboc_var (STB_LOCAL)
ffffffff816b93ea-ffffffff816b9416: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:316
Inline: False
```
**Symbols:**

```
ffffffff8176d430-ffffffff8176d53e: param_set_kgdboc_var (STB_LOCAL)
ffffffff8176d66a-ffffffff8176d6a4: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:316
Inline: False
```
**Symbols:**

```
ffffffff81787e90-ffffffff81787f9e: param_set_kgdboc_var (STB_LOCAL)
ffffffff81c083b4-ffffffff81c083ee: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:316
Inline: False
```
**Symbols:**

```
ffffffff8176b7e0-ffffffff8176b8ee: param_set_kgdboc_var (STB_LOCAL)
ffffffff81bf9f79-ffffffff81bf9fb3: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:316
Inline: False
```
**Symbols:**

```
ffffffff817f0e50-ffffffff817f0f9b: param_set_kgdboc_var (STB_LOCAL)
ffffffff81cfa7e8-ffffffff81cfa822: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:316
Inline: False
```
**Symbols:**

```
ffffffff81931380-ffffffff819314e0: param_set_kgdboc_var (STB_LOCAL)
ffffffff81ec2a59-ffffffff81ec2a93: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81a8fb00)
Location: drivers/tty/serial/kgdboc.c:328
Inline: False
```
**Symbols:**

```
ffffffff81a8fb00-ffffffff81a8fc9e: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81adb2d0)
Location: drivers/tty/serial/kgdboc.c:328
Inline: False
```
**Symbols:**

```
ffffffff81adb2d0-ffffffff81adb46e: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffffffff81b2e630)
Location: drivers/tty/serial/kgdboc.c:328
Inline: False
```
**Symbols:**

```
ffffffff81b2e630-ffffffff81b2e7ce: param_set_kgdboc_var (STB_LOCAL)
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
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (ffff8000108a8d88)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffff8000108a8d88-ffff8000108a8e98: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (c09a58a0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
c09a58a0-c09a598c: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/kgdboc.c (c0000000009401b0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
c0000000009401b0-c00000000094031c: param_set_kgdboc_var (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff8167ecb0-ffffffff8167ee1e: param_set_kgdboc_var (STB_LOCAL)
ffffffff8167ee4a-ffffffff8167ee76: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff8165dda0-ffffffff8165df0e: param_set_kgdboc_var (STB_LOCAL)
ffffffff8165df3a-ffffffff8165df66: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff816ad090-ffffffff816ad1fe: param_set_kgdboc_var (STB_LOCAL)
ffffffff816ad22a-ffffffff816ad256: param_set_kgdboc_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int param_set_kgdboc_var(const char *kmessage, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/kgdboc.c (0)
Location: drivers/tty/serial/kgdboc.c:235
Inline: False
```
**Symbols:**

```
ffffffff816c74f0-ffffffff816c765e: param_set_kgdboc_var (STB_LOCAL)
ffffffff816c768a-ffffffff816c76b6: param_set_kgdboc_var.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kernel_param *kp</code> ➡️ <code>const struct kernel_param *kp</code>
</li>
</ul>
</details>
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
