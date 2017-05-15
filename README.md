__NOTE: This is a clone of [CentrifugalPump_DesignTool](https://github.com/ina111/CentrifugalPump_DesignTool) with modifications for the Rocket Propulsion Laboratory__
## Centrifugal　Pump　Design　Tool
Centrifugal Pump design tool with EA/LOX engine
Only use for Sigle-stage certrifugal pump.
It is limited the use of approximate culcuration.
This script is New BSD License.
cf. Basic Design on Pumps by Hirohisa Takeda

## Design tool for centrifugal pump for microminiature rocket
It is a single stage centrifugal pump design tool. It is intended for ultra-small rocket engines. In the design of centrifugal pumps for general industries, Stepanoff 's design method is famous and common, but here we adopt Toyakura' s design method with reference to the paper by the Electric Works Machinery Works. It is a modified BSD license. We can not assume any responsibility regarding use.

### use
I am using python. I used scipy's fsolve to simplify the solution of cubic equation. It is output in <code>$ python centrifugalpump.py</code>. Please change the source file for parameter change.

Design parameters to decide

- Rocket thrust, specific thrust, O / F
- Pump rotation speed
- Head H
- Flow rate Q
- Specific speed Ns
- Feather exit angle beta 2
- Pump efficiency
- The pressure drop coefficient λ
- Outlet diameter D2
- Number of vanes Z
- References

## References
+ Yuki Takeda, "Fundamentals of pump design", Electric Works Machinery Machine, Vol. 29, No. 2, (2005), pp. 7 - 11 http://www.dmw.co.jp/technical/pdf/no 57. pdf
+ Stepanoff, A. J., "Centrifugal and Axial Flow Pumps (2nd Ed.)," John Wiley & Sons Inc., (1957).
+ Tomitaka Tomitaro, Takeda Yuhisa, "About the New Design Diagram of Tarbopump", Tarbo Machine No. 32 Lecture, (1994), pp. 37-42.
+ Masao Oshima, "A consideration on design constants by Stefanov for centrifugal pump impellers", Tarbo Machine, Vol. 29, (2001), pp. 221-227
+ Watanabe Keiyoshi, Yoshida Yoshiki, "Study on turbo pump main impeller diameter reduction for rocket engines", JAXA repository http://repository.tksc.jaxa.jp/dr/prc/japan/contents/AA0063736000/63736000.pdf
+ Hiroshi Aoki, Takashi Shimura, Shogo Shoji, Kenjiro Kamijo, "Design and development of turbo pump for cryogenic upper stage engine", papers of Japan Airlines Association, Vol. 53, No. 617, (2005), pp. 257-265 https : //www.jstage.jst.go.jp/article/jjsass/53/617/53_617_257/_pdf
