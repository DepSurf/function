# Function: <code>audit_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81376d90)
Location: security/apparmor/capability.c:47
Inline: False
```
```
In security/apparmor/policy.c (ffffffff8137efe0)
Location: security/apparmor/policy.c:583
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff81381b90)
Location: security/apparmor/policy_unpack.c:80
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81387490)
Location: security/apparmor/resource.c:33
Inline: False
```
```
In security/apparmor/mount.c (ffffffff8138e6c0)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff81376d90-ffffffff81376dc8: audit_cb (STB_LOCAL)
ffffffff8137efe0-ffffffff8137f01f: audit_cb (STB_LOCAL)
ffffffff81381b90-ffffffff81381c14: audit_cb (STB_LOCAL)
ffffffff81387490-ffffffff813874bb: audit_cb (STB_LOCAL)
ffffffff8138e6c0-ffffffff8138eab0: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813af800)
Location: security/apparmor/capability.c:47
Inline: False
```
```
In security/apparmor/policy.c (ffffffff813b8750)
Location: security/apparmor/policy.c:608
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff813bb750)
Location: security/apparmor/policy_unpack.c:81
Inline: False
```
```
In security/apparmor/resource.c (ffffffff813c1f30)
Location: security/apparmor/resource.c:33
Inline: False
```
```
In security/apparmor/mount.c (ffffffff813c9650)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff813af800-ffffffff813af838: audit_cb (STB_LOCAL)
ffffffff813b8750-ffffffff813b878f: audit_cb (STB_LOCAL)
ffffffff813bb750-ffffffff813bb7d4: audit_cb (STB_LOCAL)
ffffffff813c1f30-ffffffff813c1f5b: audit_cb (STB_LOCAL)
ffffffff813c9650-ffffffff813c9a40: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813c6980)
Location: security/apparmor/capability.c:47
Inline: False
```
```
In security/apparmor/policy.c (ffffffff813cfaf0)
Location: security/apparmor/policy.c:609
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff813d2c60)
Location: security/apparmor/policy_unpack.c:81
Inline: False
```
```
In security/apparmor/resource.c (ffffffff813d93d0)
Location: security/apparmor/resource.c:33
Inline: False
```
```
In security/apparmor/mount.c (ffffffff813e0cc0)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff813c6980-ffffffff813c69b8: audit_cb (STB_LOCAL)
ffffffff813cfaf0-ffffffff813cfb2f: audit_cb (STB_LOCAL)
ffffffff813d2c60-ffffffff813d2ce4: audit_cb (STB_LOCAL)
ffffffff813d93d0-ffffffff813d93fb: audit_cb (STB_LOCAL)
ffffffff813e0cc0-ffffffff813e10b0: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813dc800)
Location: security/apparmor/capability.c:48
Inline: False
```
```
In security/apparmor/policy.c (ffffffff813e3610)
Location: security/apparmor/policy.c:593
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813e57e0)
Location: security/apparmor/policy_unpack.c:80
Inline: False
```
```
In security/apparmor/resource.c (ffffffff813ea630)
Location: security/apparmor/resource.c:34
Inline: True
```
```
In security/apparmor/mount.c (ffffffff813ef9a0)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff813dc800-ffffffff813dc838: audit_cb (STB_LOCAL)
ffffffff813e3610-ffffffff813e3650: audit_cb (STB_LOCAL)
ffffffff813e57e0-ffffffff813e5864: audit_cb (STB_LOCAL)
ffffffff813ea630-ffffffff813ea6aa: audit_cb (STB_LOCAL)
ffffffff813ef9a0-ffffffff813efdba: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81403270)
Location: security/apparmor/capability.c:48
Inline: False
```
```
In security/apparmor/policy.c (ffffffff8140a460)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8140c9d0)
Location: security/apparmor/policy_unpack.c:80
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81411f30)
Location: security/apparmor/resource.c:34
Inline: True
```
```
In security/apparmor/mount.c (ffffffff814178f0)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff81403270-ffffffff814032a8: audit_cb (STB_LOCAL)
ffffffff8140a460-ffffffff8140a4a0: audit_cb (STB_LOCAL)
ffffffff8140c9d0-ffffffff8140ca54: audit_cb (STB_LOCAL)
ffffffff81411f30-ffffffff81411faa: audit_cb (STB_LOCAL)
ffffffff814178f0-ffffffff81417d0a: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814343e0)
Location: security/apparmor/capability.c:48
Inline: False
```
```
In security/apparmor/policy.c (ffffffff8143bc50)
Location: security/apparmor/policy.c:599
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e350)
Location: security/apparmor/policy_unpack.c:81
Inline: False
```
```
In security/apparmor/resource.c (ffffffff814440f0)
Location: security/apparmor/resource.c:34
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81449d70)
Location: security/apparmor/mount.c:89
Inline: False
```
**Symbols:**

```
ffffffff814343e0-ffffffff81434418: audit_cb (STB_LOCAL)
ffffffff8143bc50-ffffffff8143bc8f: audit_cb (STB_LOCAL)
ffffffff8143e350-ffffffff8143e3d9: audit_cb (STB_LOCAL)
ffffffff814440f0-ffffffff8144416a: audit_cb (STB_LOCAL)
ffffffff81449d70-ffffffff8144a19b: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81450f30)
Location: security/apparmor/capability.c:48
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81458ac0)
Location: security/apparmor/policy.c:599
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b210)
Location: security/apparmor/policy_unpack.c:81
Inline: False
```
```
In security/apparmor/resource.c (ffffffff814611a0)
Location: security/apparmor/resource.c:34
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81466cd0)
Location: security/apparmor/mount.c:90
Inline: False
```
**Symbols:**

```
ffffffff81450f30-ffffffff81450f68: audit_cb (STB_LOCAL)
ffffffff81458ac0-ffffffff81458aff: audit_cb (STB_LOCAL)
ffffffff8145b210-ffffffff8145b299: audit_cb (STB_LOCAL)
ffffffff814611a0-ffffffff8146121a: audit_cb (STB_LOCAL)
ffffffff81466cd0-ffffffff814670fb: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8147e9f0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81486240)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814887d0)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff8148e490)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81493da0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff8147e9f0-ffffffff8147ea27: audit_cb (STB_LOCAL)
ffffffff81486240-ffffffff8148627f: audit_cb (STB_LOCAL)
ffffffff814887d0-ffffffff81488859: audit_cb (STB_LOCAL)
ffffffff8148e490-ffffffff8148e50a: audit_cb (STB_LOCAL)
ffffffff81493da0-ffffffff81494183: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814986f0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff814a00f0)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2680)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff814a8350)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff814adcd0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff814986f0-ffffffff81498727: audit_cb (STB_LOCAL)
ffffffff814a00f0-ffffffff814a012f: audit_cb (STB_LOCAL)
ffffffff814a2680-ffffffff814a2709: audit_cb (STB_LOCAL)
ffffffff814a8350-ffffffff814a83ca: audit_cb (STB_LOCAL)
ffffffff814adcd0-ffffffff814ae0b3: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814f0a90)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff814f9ad0)
Location: security/apparmor/policy.c:598
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcad0)
Location: security/apparmor/policy_unpack.c:78
Inline: False
```
```
In security/apparmor/resource.c (ffffffff815056d0)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff8150cfe0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff814f0a90-ffffffff814f0ac7: audit_cb (STB_LOCAL)
ffffffff814f9ad0-ffffffff814f9b0f: audit_cb (STB_LOCAL)
ffffffff814fcad0-ffffffff814fcb59: audit_cb (STB_LOCAL)
ffffffff815056d0-ffffffff81505751: audit_cb (STB_LOCAL)
ffffffff8150cfe0-ffffffff8150d0d7: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8150dd10)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81516c00)
Location: security/apparmor/policy.c:598
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81519d20)
Location: security/apparmor/policy_unpack.c:78
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81522800)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81529e70)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff8150dd10-ffffffff8150dd47: audit_cb (STB_LOCAL)
ffffffff81516c00-ffffffff81516c3f: audit_cb (STB_LOCAL)
ffffffff81519d20-ffffffff81519da9: audit_cb (STB_LOCAL)
ffffffff81522800-ffffffff81522881: audit_cb (STB_LOCAL)
ffffffff81529e70-ffffffff81529f67: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81514720)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff8151d570)
Location: security/apparmor/policy.c:598
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520630)
Location: security/apparmor/policy_unpack.c:78
Inline: False
```
```
In security/apparmor/resource.c (ffffffff815289e0)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81530260)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff81514720-ffffffff81514757: audit_cb (STB_LOCAL)
ffffffff8151d570-ffffffff8151d5af: audit_cb (STB_LOCAL)
ffffffff81520630-ffffffff815206b9: audit_cb (STB_LOCAL)
ffffffff815289e0-ffffffff81528a61: audit_cb (STB_LOCAL)
ffffffff81530260-ffffffff81530357: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff815725e0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff8157b660)
Location: security/apparmor/policy.c:598
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157e7d0)
Location: security/apparmor/policy_unpack.c:78
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81586c80)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff8158e680)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff815725e0-ffffffff8157262e: audit_cb (STB_LOCAL)
ffffffff8157b660-ffffffff8157b69f: audit_cb (STB_LOCAL)
ffffffff8157e7d0-ffffffff8157e859: audit_cb (STB_LOCAL)
ffffffff81586c80-ffffffff81586d32: audit_cb (STB_LOCAL)
ffffffff8158e680-ffffffff8158e777: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8160f5a0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81619a20)
Location: security/apparmor/policy.c:643
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d060)
Location: security/apparmor/policy_unpack.c:76
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81627060)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff8162f730)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff8160f5a0-ffffffff8160f5f7: audit_cb (STB_LOCAL)
ffffffff81619a20-ffffffff81619a73: audit_cb (STB_LOCAL)
ffffffff8161d060-ffffffff8161d101: audit_cb (STB_LOCAL)
ffffffff81627060-ffffffff81627123: audit_cb (STB_LOCAL)
ffffffff8162f730-ffffffff8162f831: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff816c1f90)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff816cc940)
Location: security/apparmor/policy.c:717
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d0380)
Location: security/apparmor/policy_unpack.c:34
Inline: False
```
```
In security/apparmor/resource.c (ffffffff816db060)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff816e4370)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff816c1f90-ffffffff816c1fe7: audit_cb (STB_LOCAL)
ffffffff816cc940-ffffffff816cc987: audit_cb (STB_LOCAL)
ffffffff816d0380-ffffffff816d0409: audit_cb (STB_LOCAL)
ffffffff816db060-ffffffff816db117: audit_cb (STB_LOCAL)
ffffffff816e4370-ffffffff816e4447: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff816fabc0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff817053e0)
Location: security/apparmor/policy.c:752
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81708fd0)
Location: security/apparmor/policy_unpack.c:34
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81714750)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff8171d9c0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff816fabc0-ffffffff816fac17: audit_cb (STB_LOCAL)
ffffffff817053e0-ffffffff81705427: audit_cb (STB_LOCAL)
ffffffff81708fd0-ffffffff81709059: audit_cb (STB_LOCAL)
ffffffff81714750-ffffffff81714807: audit_cb (STB_LOCAL)
ffffffff8171d9c0-ffffffff8171da97: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff817377d0)
Location: security/apparmor/capability.c:45
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81742ce0)
Location: security/apparmor/policy.c:782
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81746a60)
Location: security/apparmor/policy_unpack.c:35
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81753160)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff8175c410)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff817377d0-ffffffff81737827: audit_cb (STB_LOCAL)
ffffffff81742ce0-ffffffff81742d27: audit_cb (STB_LOCAL)
ffffffff81746a60-ffffffff81746ae9: audit_cb (STB_LOCAL)
ffffffff81753160-ffffffff81753217: audit_cb (STB_LOCAL)
ffffffff8175c410-ffffffff8175c4e7: audit_cb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffff80001058e2f0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffff800010595e40)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff8000105982d8)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffff80001059ea38)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffff8000105a53f0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffff80001058e2f0-ffff80001058e340: audit_cb (STB_LOCAL)
ffff800010595e40-ffff800010595e94: audit_cb (STB_LOCAL)
ffff8000105982d8-ffff800010598380: audit_cb (STB_LOCAL)
ffff80001059ea38-ffff80001059ead0: audit_cb (STB_LOCAL)
ffff8000105a53f0-ffff8000105a579c: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (c073f170)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (c0746f54)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (c07493a4)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (c074f7e0)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (c07554bc)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
c073f170-c073f1b4: audit_cb (STB_LOCAL)
c0746f54-c0746fa0: audit_cb (STB_LOCAL)
c07493a4-c0749440: audit_cb (STB_LOCAL)
c074f7e0-c074f87c: audit_cb (STB_LOCAL)
c07554bc-c075589c: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (c000000000700dd0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (c00000000070b5c0)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070eec0)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (c000000000718510)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (c0000000007211d0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
c000000000700dd0-c000000000700e44: audit_cb (STB_LOCAL)
c00000000070b5c0-c00000000070b638: audit_cb (STB_LOCAL)
c00000000070eec0-c00000000070efac: audit_cb (STB_LOCAL)
c000000000718510-c0000000007185d8: audit_cb (STB_LOCAL)
c0000000007211d0-c0000000007216b8: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffe0003dc308)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffe0003e2d7c)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e4d40)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffe0003e9ef8)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffe0003eefb6)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffe0003dc308-ffffffe0003dc35e: audit_cb (STB_LOCAL)
ffffffe0003e2d7c-ffffffe0003e2dc8: audit_cb (STB_LOCAL)
ffffffe0003e4d40-ffffffe0003e4dd6: audit_cb (STB_LOCAL)
ffffffe0003e9ef8-ffffffe0003e9f80: audit_cb (STB_LOCAL)
ffffffe0003eefb6-ffffffe0003ef3be: audit_cb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81490cd0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff814986d0)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149ac60)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff814a0930)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff814a62b0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff81490cd0-ffffffff81490d07: audit_cb (STB_LOCAL)
ffffffff814986d0-ffffffff8149870f: audit_cb (STB_LOCAL)
ffffffff8149ac60-ffffffff8149ace9: audit_cb (STB_LOCAL)
ffffffff814a0930-ffffffff814a09aa: audit_cb (STB_LOCAL)
ffffffff814a62b0-ffffffff814a6693: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814816f0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff814890f0)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b680)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff81491350)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff81496cd0)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff814816f0-ffffffff81481727: audit_cb (STB_LOCAL)
ffffffff814890f0-ffffffff8148912f: audit_cb (STB_LOCAL)
ffffffff8148b680-ffffffff8148b709: audit_cb (STB_LOCAL)
ffffffff81491350-ffffffff814913ca: audit_cb (STB_LOCAL)
ffffffff81496cd0-ffffffff814970b3: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8148cd70)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff81494770)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81496d00)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff8149c9d0)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff814a2350)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff8148cd70-ffffffff8148cda7: audit_cb (STB_LOCAL)
ffffffff81494770-ffffffff814947af: audit_cb (STB_LOCAL)
ffffffff81496d00-ffffffff81496d89: audit_cb (STB_LOCAL)
ffffffff8149c9d0-ffffffff8149ca4a: audit_cb (STB_LOCAL)
ffffffff814a2350-ffffffff814a2733: audit_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void audit_cb(struct audit_buffer *ab, void *va);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814a4bb0)
Location: security/apparmor/capability.c:44
Inline: False
```
```
In security/apparmor/policy.c (ffffffff814ac790)
Location: security/apparmor/policy.c:594
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814aedd0)
Location: security/apparmor/policy_unpack.c:77
Inline: False
```
```
In security/apparmor/resource.c (ffffffff814b4f60)
Location: security/apparmor/resource.c:30
Inline: True
```
```
In security/apparmor/mount.c (ffffffff814bab10)
Location: security/apparmor/mount.c:86
Inline: False
```
**Symbols:**

```
ffffffff814a4bb0-ffffffff814a4be7: audit_cb (STB_LOCAL)
ffffffff814ac790-ffffffff814ac7cf: audit_cb (STB_LOCAL)
ffffffff814aedd0-ffffffff814aee59: audit_cb (STB_LOCAL)
ffffffff814b4f60-ffffffff814b4fda: audit_cb (STB_LOCAL)
ffffffff814bab10-ffffffff814baef3: audit_cb (STB_LOCAL)
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
