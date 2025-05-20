# Function: <code>export_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81428450)
Location: drivers/gpio/gpiolib-sysfs.c:441
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8142d6e0)
Location: drivers/pwm/sysfs.c:247
Inline: False
```
**Symbols:**

```
ffffffff81428450-ffffffff8142855a: export_store (STB_LOCAL)
ffffffff8142d6e0-ffffffff8142d837: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81473750)
Location: drivers/gpio/gpiolib-sysfs.c:441
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81478a50)
Location: drivers/pwm/sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff81473750-ffffffff81473856: export_store (STB_LOCAL)
ffffffff81478a50-ffffffff81478bc7: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495970)
Location: drivers/gpio/gpiolib-sysfs.c:441
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81499de0)
Location: drivers/pwm/sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff81495970-ffffffff81495a76: export_store (STB_LOCAL)
ffffffff81499de0-ffffffff81499f57: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149f380)
Location: drivers/gpio/gpiolib-sysfs.c:447
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff814a3a30)
Location: drivers/pwm/sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff8149f380-ffffffff8149f4ac: export_store (STB_LOCAL)
ffffffff814a3a30-ffffffff814a3ba9: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814ddec0)
Location: drivers/gpio/gpiolib-sysfs.c:447
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff814e27a0)
Location: drivers/pwm/sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff814ddec0-ffffffff814ddfec: export_store (STB_LOCAL)
ffffffff814e27a0-ffffffff814e2919: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:458
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81511fb0)
Location: drivers/pwm/sysfs.c:308
Inline: False
```
**Symbols:**

```
ffffffff8150d070-ffffffff8150d173: export_store (STB_LOCAL)
ffffffff8150d31d-ffffffff8150d343: export_store.cold.6 (STB_LOCAL)
ffffffff81511fb0-ffffffff81512149: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff815276d0)
Location: drivers/pwm/sysfs.c:318
Inline: False
```
**Symbols:**

```
ffffffff815225a0-ffffffff81522696: export_store (STB_LOCAL)
ffffffff81522924-ffffffff81522947: export_store.cold.3 (STB_LOCAL)
ffffffff815276d0-ffffffff81527893: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81556990)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff81550ad0-ffffffff81550bcc: export_store (STB_LOCAL)
ffffffff81550e44-ffffffff81550e67: export_store.cold (STB_LOCAL)
ffffffff81556990-ffffffff81556b48: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81577fb0)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff81571f70-ffffffff8157206c: export_store (STB_LOCAL)
ffffffff815722e4-ffffffff81572307: export_store.cold (STB_LOCAL)
ffffffff81577fb0-ffffffff81578168: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8161cdf0)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff816165f0-ffffffff816166ec: export_store (STB_LOCAL)
ffffffff8161687a-ffffffff8161689d: export_store.cold (STB_LOCAL)
ffffffff8161cdf0-ffffffff8161cea1: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:454
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81643520)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff8163cf90-ffffffff8163d08c: export_store (STB_LOCAL)
ffffffff81bf688c-ffffffff81bf68af: export_store.cold (STB_LOCAL)
ffffffff81643520-ffffffff816435d1: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:454
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81626340)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff81620ac0-ffffffff81620be7: export_store (STB_LOCAL)
ffffffff81be87b4-ffffffff81be87fa: export_store.cold (STB_LOCAL)
ffffffff81626340-ffffffff816263f1: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:446
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81695b80)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff81690080-ffffffff816901a8: export_store (STB_LOCAL)
ffffffff81ce2596-ffffffff81ce25dc: export_store.cold (STB_LOCAL)
ffffffff81695b80-ffffffff81695c31: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:429
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff817b6950)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff817af120-ffffffff817af260: export_store (STB_LOCAL)
ffffffff81ea8f82-ffffffff81ea8fbe: export_store.cold (STB_LOCAL)
ffffffff817b6950-ffffffff817b6a14: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c8700)
Location: drivers/gpio/gpiolib-sysfs.c:429
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff818d11b0)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff818c8700-ffffffff818c887c: export_store (STB_LOCAL)
ffffffff818d11b0-ffffffff818d1274: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t export_store(const struct class *class, const struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b6b0)
Location: drivers/gpio/gpiolib-sysfs.c:440
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff819141a0)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff8190b6b0-ffffffff8190b82c: export_store (STB_LOCAL)
ffffffff819141a0-ffffffff81914264: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t export_store(const struct class *class, const struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff819533d0)
Location: drivers/gpio/gpiolib-sysfs.c:441
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8195c110)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff819533d0-ffffffff81953547: export_store (STB_LOCAL)
ffffffff8195c110-ffffffff8195c1d4: export_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9b78)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffff8000106d9bb8)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffff8000106c9b78-ffff8000106c9cec: export_store (STB_LOCAL)
ffff8000106d9bb8-ffff8000106d9df4: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0866e7c)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (c08764c8)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
c0866e7c-c0866ff0: export_store (STB_LOCAL)
c08764c8-c087668c: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0000000008478c0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (c000000000851680)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
c0000000008478c0-c000000000847a84: export_store (STB_LOCAL)
c000000000851680-c000000000851928: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004acdb2)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffe0004b28cc)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffe0004acdb2-ffffffe0004acee0: export_store (STB_LOCAL)
ffffffe0004b28cc-ffffffe0004b2a52: export_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8156cdc0)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff81567730-ffffffff8156782c: export_store (STB_LOCAL)
ffffffff81567aa4-ffffffff81567ac7: export_store.cold (STB_LOCAL)
ffffffff8156cdc0-ffffffff8156cf78: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
**Symbols:**

```
ffffffff81558580-ffffffff8155867c: export_store (STB_LOCAL)
ffffffff815588f4-ffffffff81558917: export_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8156bd00)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff815662a0-ffffffff8156639c: export_store (STB_LOCAL)
ffffffff81566614-ffffffff81566637: export_store.cold (STB_LOCAL)
ffffffff8156bd00-ffffffff8156beb8: export_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t export_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:453
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81586200)
Location: drivers/pwm/sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff815801c0-ffffffff815802bc: export_store (STB_LOCAL)
ffffffff81580534-ffffffff81580557: export_store.cold (STB_LOCAL)
ffffffff81586200-ffffffff815863b8: export_store (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct class_attribute *attr</code> ➡️ <code>const struct class_attribute *attr</code>
</li>
</ul>
</details>
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
