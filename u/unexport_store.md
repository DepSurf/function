# Function: <code>unexport_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81427f60)
Location: drivers/gpio/gpiolib-sysfs.c:483
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8142d3e0)
Location: drivers/pwm/sysfs.c:275
Inline: False
```
**Symbols:**

```
ffffffff81427f60-ffffffff81428022: unexport_store (STB_LOCAL)
ffffffff8142d3e0-ffffffff8142d4a2: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81473260)
Location: drivers/gpio/gpiolib-sysfs.c:483
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff814785c0)
Location: drivers/pwm/sysfs.c:334
Inline: False
```
**Symbols:**

```
ffffffff81473260-ffffffff81473321: unexport_store (STB_LOCAL)
ffffffff814785c0-ffffffff8147867e: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495480)
Location: drivers/gpio/gpiolib-sysfs.c:483
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81499980)
Location: drivers/pwm/sysfs.c:334
Inline: False
```
**Symbols:**

```
ffffffff81495480-ffffffff81495541: unexport_store (STB_LOCAL)
ffffffff81499980-ffffffff81499a10: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149ee80)
Location: drivers/gpio/gpiolib-sysfs.c:490
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff814a35c0)
Location: drivers/pwm/sysfs.c:334
Inline: False
```
**Symbols:**

```
ffffffff8149ee80-ffffffff8149ef5d: unexport_store (STB_LOCAL)
ffffffff814a35c0-ffffffff814a3652: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd9c0)
Location: drivers/gpio/gpiolib-sysfs.c:490
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff814e2330)
Location: drivers/pwm/sysfs.c:334
Inline: False
```
**Symbols:**

```
ffffffff814dd9c0-ffffffff814dda9d: unexport_store (STB_LOCAL)
ffffffff814e2330-ffffffff814e23c2: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:505
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81511b50)
Location: drivers/pwm/sysfs.c:336
Inline: False
```
**Symbols:**

```
ffffffff8150cbb0-ffffffff8150cc69: unexport_store (STB_LOCAL)
ffffffff8150d2c1-ffffffff8150d2e7: unexport_store.cold.3 (STB_LOCAL)
ffffffff81511b50-ffffffff81511be2: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81527280)
Location: drivers/pwm/sysfs.c:346
Inline: False
```
**Symbols:**

```
ffffffff81522210-ffffffff815222bc: unexport_store (STB_LOCAL)
ffffffff81522901-ffffffff81522924: unexport_store.cold.2 (STB_LOCAL)
ffffffff81527280-ffffffff81527312: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff815566c0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff81550720-ffffffff815507cf: unexport_store (STB_LOCAL)
ffffffff81550e21-ffffffff81550e44: unexport_store.cold (STB_LOCAL)
ffffffff815566c0-ffffffff8155674d: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81577ce0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff81571bd0-ffffffff81571c7f: unexport_store (STB_LOCAL)
ffffffff815722c1-ffffffff815722e4: unexport_store.cold (STB_LOCAL)
ffffffff81577ce0-ffffffff81577d6d: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8161c9c0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff81615f00-ffffffff81615faf: unexport_store (STB_LOCAL)
ffffffff81616821-ffffffff81616844: unexport_store.cold (STB_LOCAL)
ffffffff8161c9c0-ffffffff8161ca51: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:501
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81642f90)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff8163c880-ffffffff8163c92f: unexport_store (STB_LOCAL)
ffffffff81bf6833-ffffffff81bf6856: unexport_store.cold (STB_LOCAL)
ffffffff81642f90-ffffffff81643025: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:509
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81625db0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff816203c0-ffffffff8162046f: unexport_store (STB_LOCAL)
ffffffff81be875b-ffffffff81be877e: unexport_store.cold (STB_LOCAL)
ffffffff81625db0-ffffffff81625e45: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:498
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff816955a0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff8168f8e0-ffffffff8168f98c: unexport_store (STB_LOCAL)
ffffffff81ce2528-ffffffff81ce254b: unexport_store.cold (STB_LOCAL)
ffffffff816955a0-ffffffff81695635: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:481
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff817b6270)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff817aec50-ffffffff817aed10: unexport_store (STB_LOCAL)
ffffffff81ea8f2c-ffffffff81ea8f4f: unexport_store.cold (STB_LOCAL)
ffffffff817b6270-ffffffff817b6318: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c81c0)
Location: drivers/gpio/gpiolib-sysfs.c:481
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff818d07e0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff818c81c0-ffffffff818c829c: unexport_store (STB_LOCAL)
ffffffff818d07e0-ffffffff818d0888: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(const struct class *class, const struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b9b0)
Location: drivers/gpio/gpiolib-sysfs.c:492
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81913770)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff8190b9b0-ffffffff8190ba9e: unexport_store (STB_LOCAL)
ffffffff81913770-ffffffff81913818: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(const struct class *class, const struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff819536d0)
Location: drivers/gpio/gpiolib-sysfs.c:495
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8195b6b0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff819536d0-ffffffff819537be: unexport_store (STB_LOCAL)
ffffffff8195b6b0-ffffffff8195b753: unexport_store (STB_LOCAL)
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
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9580)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffff8000106d9b00)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffff8000106c9580-ffff8000106c9690: unexport_store (STB_LOCAL)
ffff8000106d9b00-ffff8000106d9bb4: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0866a54)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (c08761c8)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
c0866a54-c0866b64: unexport_store (STB_LOCAL)
c08761c8-c0876270: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c000000000847140)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (c000000000851260)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
c000000000847140-c00000000084728c: unexport_store (STB_LOCAL)
c000000000851260-c000000000851350: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004aca00)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffe0004b256c)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffe0004aca00-ffffffe0004acad8: unexport_store (STB_LOCAL)
ffffffe0004b256c-ffffffe0004b25d8: unexport_store (STB_LOCAL)
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
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8156caf0)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff81567390-ffffffff8156743f: unexport_store (STB_LOCAL)
ffffffff81567a81-ffffffff81567aa4: unexport_store.cold (STB_LOCAL)
ffffffff8156caf0-ffffffff8156cb7d: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
**Symbols:**

```
ffffffff815581e0-ffffffff8155828f: unexport_store (STB_LOCAL)
ffffffff815588d1-ffffffff815588f4: unexport_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff8156ba30)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff81565f00-ffffffff81565faf: unexport_store (STB_LOCAL)
ffffffff815665f1-ffffffff81566614: unexport_store.cold (STB_LOCAL)
ffffffff8156ba30-ffffffff8156babd: unexport_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t unexport_store(struct class *class, struct class_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:500
Inline: False
```
```
In drivers/pwm/sysfs.c (ffffffff81585f30)
Location: drivers/pwm/sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff8157fe20-ffffffff8157fecf: unexport_store (STB_LOCAL)
ffffffff81580511-ffffffff81580534: unexport_store.cold (STB_LOCAL)
ffffffff81585f30-ffffffff81585fbd: unexport_store (STB_LOCAL)
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
