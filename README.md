<!doctype html>
<html itemscope="" itemtype="http://schema.org/SearchResultsPage" lang="vi">
    <head>
        <meta charset="UTF-8">
        <meta content="dark light" name="color-scheme">
        <meta content="origin" name="referrer">
        <meta content="AnDXABl+YshzbjO2LKtXm2NvzMpolW048PCnss57tEzJg/4ZSfRVrdMVzAfbVsbvwgJNvkS6jo6fxAubQzQqEA4AAAByeyJvcmlnaW4iOiJodHRwczovL2dvb2dsZS5jb20udm46NDQzIiwiZmVhdHVyZSI6IkxvbmdBbmltYXRpb25GcmFtZVRpbWluZyIsImV4cGlyeSI6MTcwOTY4MzE5OSwiaXNTdWJkb21haW4iOnRydWV9" http-equiv="origin-trial">
        <meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image">
        <title>code mẫu - Tìm trên Google</title>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                var b = window.addEventListener;
                window.addEventListener = function(a, c, d) {
                    "unload" !== a && b(a, c, d)
                }
                ;
            }
            ).call(this);
            (function() {
                var _g = {
                    kEI: 'WrGXZcTbGIHc1e8P9Y2o8A8',
                    kEXPI: '31',
                    u: 'c17706b2',
                    kBL: 'Qwmp',
                    kOPI: 89978449
                };
                (function() {
                    var a;
                    (null == (a = window.google) ? 0 : a.stvsc) ? google.kEI = _g.kEI : window.google = _g;
                }
                ).call(this);
            }
            )();
            (function() {
                google.sn = 'web';
                google.kHL = 'vi';
            }
            )();
            (function() {
                var h = this || self;
                function l() {
                    return void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null
                }
                ;var m, n = [];
                function p(a) {
                    for (var b; a && (!a.getAttribute || !(b = a.getAttribute("eid"))); )
                        a = a.parentNode;
                    return b || m
                }
                function q(a) {
                    for (var b = null; a && (!a.getAttribute || !(b = a.getAttribute("leid"))); )
                        a = a.parentNode;
                    return b
                }
                function r(a) {
                    /^http:/i.test(a) && "https:" === window.location.protocol && (google.ml && google.ml(Error("a"), !1, {
                        src: a,
                        glmm: 1
                    }),
                    a = "");
                    return a
                }
                function t(a, b, c, d, k) {
                    var e = "";
                    -1 === b.search("&ei=") && (e = "&ei=" + p(d),
                    -1 === b.search("&lei=") && (d = q(d)) && (e += "&lei=" + d));
                    d = "";
                    var g = -1 === b.search("&cshid=") && "slh" !== a
                      , f = [];
                    f.push(["zx", Date.now().toString()]);
                    h._cshid && g && f.push(["cshid", h._cshid]);
                    c = c();
                    null != c && f.push(["opi", c.toString()]);
                    for (c = 0; c < f.length; c++) {
                        if (0 === c || 0 < c)
                            d += "&";
                        d += f[c][0] + "=" + f[c][1]
                    }
                    return "/" + (k || "gen_204") + "?atyp=i&ct=" + String(a) + "&cad=" + (b + e + d)
                }
                ;m = google.kEI;
                google.getEI = p;
                google.getLEI = q;
                google.ml = function() {
                    return null
                }
                ;
                google.log = function(a, b, c, d, k, e) {
                    e = void 0 === e ? l : e;
                    c || (c = t(a, b, e, d, k));
                    if (c = r(c)) {
                        a = new Image;
                        var g = n.length;
                        n[g] = a;
                        a.onerror = a.onload = a.onabort = function() {
                            delete n[g]
                        }
                        ;
                        a.src = c
                    }
                }
                ;
                google.logUrl = function(a, b) {
                    b = void 0 === b ? l : b;
                    return t("", a, b)
                }
                ;
            }
            ).call(this);
            (function() {
                google.y = {};
                google.sy = [];
                google.x = function(a, b) {
                    if (a)
                        var c = a.id;
                    else {
                        do
                            c = Math.random();
                        while (google.y[c])
                    }
                    google.y[c] = [a, b];
                    return !1
                }
                ;
                google.sx = function(a) {
                    google.sy.push(a)
                }
                ;
                google.lm = [];
                google.plm = function(a) {
                    google.lm.push.apply(google.lm, a)
                }
                ;
                google.lq = [];
                google.load = function(a, b, c) {
                    google.lq.push([[a], b, c])
                }
                ;
                google.loadAll = function(a, b) {
                    google.lq.push([a, b])
                }
                ;
                google.bx = !1;
                google.lx = function() {}
                ;
                var d = [];
                google.fce = function(a, b, c, e) {
                    d.push([a, b, c, e])
                }
                ;
                google.qce = d;
            }
            ).call(this);
            google.f = {};
            (function() {
                document.documentElement.addEventListener("submit", function(b) {
                    var a;
                    if (a = b.target) {
                        var c = a.getAttribute("data-submitfalse");
                        a = "1" === c || "q" === c && !a.elements.q.value ? !0 : !1
                    } else
                        a = !1;
                    a && (b.preventDefault(),
                    b.stopPropagation())
                }, !0);
                document.documentElement.addEventListener("click", function(b) {
                    var a;
                    a: {
                        for (a = b.target; a && a !== document.documentElement; a = a.parentElement)
                            if ("A" === a.tagName) {
                                a = "1" === a.getAttribute("data-nohref");
                                break a
                            }
                        a = !1
                    }
                    a && b.preventDefault()
                }, !0);
            }
            ).call(this);
            (function() {
                google.hs = {
                    h: true,
                    nhs: false,
                    sie: false
                };
            }
            )();
            (function() {
                google.c = {
                    bfrt: false,
                    bfrte: true,
                    bofr: true,
                    btfi: false,
                    c4t: true,
                    cap: 2000,
                    cgpbc: false,
                    di: false,
                    fla: false,
                    fli: false,
                    frt: false,
                    frvt: true,
                    gl: false,
                    idt: 16,
                    inpp: 98,
                    inpsr: 0.01,
                    irsf: false,
                    lfdt: 50,
                    lfsr: 0.01,
                    lhc: false,
                    linp: true,
                    llf: true,
                    llt: false,
                    lsb: true,
                    lsbsr: 0.01,
                    mais: true,
                    marb: true,
                    raf: false,
                    si: true,
                    sidt: 200,
                    sisr: 0.01,
                    sxs: false,
                    taf: true,
                    timl: false,
                    vis: true,
                    wh0: false,
                    whu: false
                };
            }
            )();
            (function() {
                var n = this || self;
                var p = window.performance;
                function aa(a, b, c) {
                    a: {
                        for (var d = a; d && d !== b; d = d.parentElement)
                            if ("hidden" === d.style.overflow || "G-EXPANDABLE-CONTENT" === d.tagName && "hidden" === getComputedStyle(d).getPropertyValue("overflow")) {
                                b = d;
                                break a
                            }
                        b = null
                    }
                    if (!b)
                        return !1;
                    a = c(a);
                    c = c(b);
                    return a.bottom < c.top || a.top >= c.bottom || a.right < c.left || a.left >= c.right
                }
                function ba(a) {
                    return "none" === a.style.display ? !0 : document.defaultView && document.defaultView.getComputedStyle ? (a = document.defaultView.getComputedStyle(a),
                    !!a && ("hidden" === a.visibility || "0px" === a.height && "0px" === a.width)) : !1
                }
                function ca(a, b, c, d, f) {
                    var g = f(a)
                      , l = g.left + (c ? 0 : window.pageXOffset)
                      , k = g.top + (c ? 0 : window.pageYOffset)
                      , h = g.width
                      , m = g.height
                      , e = 0;
                    if (!b && 0 >= m && 0 >= h)
                        return e;
                    b = window.innerHeight || document.documentElement.clientHeight;
                    0 > k + m ? e = 2 : k >= b && (e = 4);
                    if (0 > l + h || l >= (window.innerWidth || document.documentElement.clientWidth))
                        e |= 8;
                    else if (d) {
                        g = g.left;
                        if (!c)
                            for (; a && a !== d; a = a.parentElement)
                                g += a.scrollLeft;
                        d = f(d);
                        if (g + h < d.left || g >= d.right)
                            e |= 8
                    }
                    e || (e = 1,
                    k + m > b && (e |= 4));
                    return e
                }
                ;var q = google.c.bfrt
                  , r = google.c.bfrte
                  , da = google.c.cap
                  , t = google.c.cgpbc
                  , ea = google.c.vis
                  , fa = google.c.irsf
                  , ha = google.c.marb
                  , ia = google.c.taf
                  , u = google.c.frt
                  , v = google.c.frvt
                  , w = google.c.timl;
                function y(a, b) {
                    google.tick("load", a, b)
                }
                function z(a, b) {
                    google.c.e("load", a, String(b))
                }
                function A(a) {
                    return Math.floor(a.getBoundingClientRect().top + window.pageYOffset)
                }
                function B(a, b, c, d) {
                    a.addEventListener ? a.addEventListener(b, c, d || !1) : a.attachEvent && a.attachEvent("on" + b, c)
                }
                function C(a, b, c, d) {
                    "addEventListener"in a ? a.removeEventListener(b, c, d || !1) : a.attachEvent && a.detachEvent("on" + b, c)
                }
                ;var ja = function(a) {
                    this.g = a;
                    this.v = [];
                    this.B = this.g.hasAttribute("data-noaft");
                    this.j = !!this.g.getAttribute("data-deferred");
                    var b;
                    if (b = !this.j)
                        a: {
                            for (b = 0; b < D.length; ++b)
                                if (a.getAttribute("data-" + D[b])) {
                                    b = !0;
                                    break a
                                }
                            b = !1
                        }
                    this.h = b;
                    this.F = this.g.hasAttribute("data-bsrc");
                    (a = this.g.src) && this.h && (this.C = a);
                    this.h && this.g.setAttribute("data-lzy_", "1");
                    (this.l = ("string" !== typeof a || !a || this.g.complete) && !this.j && !this.h || this.B) || E(this);
                    ea && F(this)
                }
                  , E = function(a) {
                    google.rll(a.g, !0, function() {
                        var b = Date.now();
                        if (a.C && a.g.src === a.C || "1" === a.g.getAttribute("data-deferred"))
                            E(a);
                        else if (!a.i) {
                            a.j && a.g.setAttribute("data-deferred", "3");
                            a.i = b;
                            b = a.i;
                            for (var c = 0; c < a.v.length; ++c)
                                a.v[c](b);
                            a.v.length = 0
                        }
                    })
                }
                  , F = function(a) {
                    if (void 0 === a.A) {
                        var b = a.g;
                        var c = void 0;
                        t && (c = G(b));
                        if (!c)
                            for (c = b; c && "center_col" !== c.id; )
                                c = c.parentElement;
                        c || t || (c = G(b));
                        var d = b.parentElement;
                        if (d && ("G-IMG" === d.tagName || d.classList.contains("uhHOwf")) && (d.style.height || d.style.width)) {
                            var f = d.getBoundingClientRect()
                              , g = b.getBoundingClientRect();
                            if (f.height <= g.height || f.width <= g.width)
                                b = d
                        }
                        b = google.cv(b, !1, void 0, c);
                        a.A = b
                    }
                    return a.A
                }
                  , D = "src bsrc url ll image img-url".split(" ");
                function G(a) {
                    for (; a; a = a.parentElement)
                        if ("G-SCROLLING-CAROUSEL" === a.tagName)
                            return a;
                    return null
                }
                google.c.iim = google.c.iim || {};
                var H = google.c.iim
                  , ka = 0;
                function la(a) {
                    var b = String(a.getAttribute("data-csiid") || ++ka);
                    H[b] || (a.setAttribute("data-csiid", b),
                    H[b] = new ja(a));
                    return H[b]
                }
                function I(a, b) {
                    b = (b || document).getElementsByTagName("img");
                    for (var c = 0, d = b.length; c < d; ++c)
                        a(la(b[c]))
                }
                ;google.timers = {};
                google.startTick = function(a) {
                    google.timers[a] = {
                        t: {
                            start: Date.now()
                        },
                        e: {},
                        m: {}
                    }
                }
                ;
                google.tick = function(a, b, c) {
                    google.timers[a] || google.startTick(a);
                    c = void 0 !== c ? c : Date.now();
                    b instanceof Array || (b = [b]);
                    for (var d = 0, f; f = b[d++]; )
                        google.timers[a].t[f] = c
                }
                ;
                google.c.e = function(a, b, c) {
                    google.timers[a].e[b] = c
                }
                ;
                google.c.b = function(a, b) {
                    b = google.timers[b || "load"].m;
                    b[a] && google.ml(Error("a"), !1, {
                        m: a
                    });
                    b[a] = !0
                }
                ;
                google.c.u = function(a, b) {
                    var c = google.timers[b || "load"];
                    b = c.m;
                    if (b[a]) {
                        b[a] = !1;
                        for (a in b)
                            if (b[a])
                                return !1;
                        google.csiReport(c, "all");
                        return !0
                    }
                    c = "";
                    for (var d in b)
                        c += d + ":" + b[d] + ";";
                    google.ml(Error("b"), !1, {
                        m: a,
                        b: !1 === b[a],
                        s: c
                    });
                    return !1
                }
                ;
                google.rll = function(a, b, c) {
                    function d(f) {
                        c(f);
                        C(a, "load", d);
                        C(a, "error", d)
                    }
                    B(a, "load", d);
                    b && B(a, "error", d)
                }
                ;
                n.google.aft = function(a) {
                    a.setAttribute("data-iml", String(Date.now()))
                }
                ;
                google.startTick("load");
                google.tick("load", "hst");
                var J = google.timers.load;
                if (!google.stvsc)
                    a: {
                        var ma = J.t;
                        if (p) {
                            var K = p.timing;
                            if (K) {
                                var na = K.navigationStart
                                  , L = K.responseStart;
                                if (L > na && L <= ma.start) {
                                    ma.start = L;
                                    J.wsrt = L - na;
                                    break a
                                }
                            }
                            p.now && (J.wsrt = Math.floor(p.now()))
                        }
                    }
                google.c.b("xe", "load");
                var oa;
                if (null == (oa = google.stvsc) ? 0 : oa.start)
                    google.timers.load.t.start = google.stvsc.start;
                function pa(a) {
                    if ("hidden" === document.visibilityState) {
                        google.c.fh = a;
                        var b;
                        window.performance && window.performance.timing && (b = Math.floor(window.performance.timing.navigationStart + a));
                        google.tick("load", "fht", b);
                        return !0
                    }
                    return !1
                }
                function qa(a) {
                    pa(a.timeStamp) && C(document, "visibilitychange", qa, !0)
                }
                google.c.fh = Infinity;
                B(document, "visibilitychange", qa, !0);
                pa(0);
                google.cv = function(a, b, c, d) {
                    if (!a || !b && ba(a))
                        return 0;
                    if (!a.getBoundingClientRect)
                        return 1;
                    var f = function(g) {
                        return g.getBoundingClientRect()
                    };
                    return !b && aa(a, d, f) ? 0 : ca(a, b, c, d, f)
                }
                ;
                function M(a) {
                    try {
                        a()
                    } catch (b) {
                        google.ml(b, !1)
                    }
                }
                function N(a) {
                    if (null !== google.aftq && (2 === google.fevent || 3 === google.fevent ? google.fevent : 1) & a) {
                        google.tick("load", "aftqf", Date.now());
                        var b;
                        a = 0;
                        for (var c; c = null == (b = google.aftq) ? void 0 : b[a++]; )
                            M(c);
                        google.aftq = null
                    }
                }
                google.caft = function(a, b) {
                    null === google.aftq ? M(a) : (google.aftq = google.aftq || [],
                    google.aftq.push(a),
                    b && window.setTimeout(function() {
                        google.aftq && (google.aftq = google.aftq.filter(function(c) {
                            return a !== c
                        }),
                        M(a))
                    }, b))
                }
                ;
                function O() {
                    return window.performance && window.performance.navigation && window.performance.navigation.type
                }
                ;var ra = window.location
                  , sa = "aft afti aftr afts cbs cbt fht frt frts frvt hct hst prt sct".split(" ");
                function P(a) {
                    return (a = ra.search.match(new RegExp("[?&]" + a + "=(\\d+)"))) ? Number(a[1]) : -1
                }
                function ta(a) {
                    var b = google.timers.load
                      , c = b.m;
                    if (!c || !c.prs) {
                        var d = O() ? 0 : P("qsubts");
                        0 < d && (c = P("fbts"),
                        0 < c && (b.t.start = Math.max(d, c)));
                        var f = b.t
                          , g = f.start;
                        c = {
                            wsrt: b.wsrt || 0
                        };
                        if (g)
                            for (var l = 0, k; k = sa[l++]; ) {
                                var h = f[k];
                                h && (c[k] = Math.max(h - g, 0))
                            }
                        0 < d && (c.gsasrt = b.t.start - d);
                        b = b.e;
                        a = "/gen_204?s=" + google.sn + "&t=" + a + "&atyp=csi&ei=" + google.kEI + "&rt=";
                        d = "";
                        for (var m in c)
                            a += "" + d + m + "." + c[m],
                            d = ",";
                        for (var e in b)
                            a += "&" + e + "=" + b[e];
                        m = a;
                        e = "";
                        a = [];
                        n._cshid && a.push(["cshid", n._cshid]);
                        b = void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null;
                        null != b && a.push(["opi", b.toString()]);
                        for (b = 0; b < a.length; b++) {
                            if (0 === b || 0 < b)
                                e += "&";
                            e += a[b][0] + "=" + a[b][1]
                        }
                        a = m + e;
                        2 === O() && (a += "&bb=1");
                        1 === O() && (a += "&r=1");
                        "gsasrt"in c && (c = P("qsd"),
                        0 < c && (a += "&qsd=" + c));
                        c = a;
                        "function" === typeof navigator.sendBeacon ? navigator.sendBeacon(c, "") : google.log("", "", c)
                    }
                }
                ;function ua(a) {
                    a && google.tick("load", "cbs", a);
                    google.tick("load", "cbt");
                    ta("cap")
                }
                ;var S = function() {
                    var a = R;
                    a.h--;
                    !a.h && a.g && (a.g(),
                    a.g = null)
                }
                  , va = function(a) {
                    var b = R;
                    b.g = a;
                    !b.h && b.g && (b.g(),
                    b.g = null)
                }
                  , R = new function() {
                    this.h = 0;
                    this.g = null
                }
                ;
                function T(a, b, c) {
                    function d(h) {
                        k = Math.max(k, h);
                        ++l;
                        f || g !== l || c(k)
                    }
                    var f = !0
                      , g = 0
                      , l = 0
                      , k = 0;
                    I(function(h) {
                        a(h) && (++g,
                        h.i || h.l ? d(h.i || 0) : h.v.push(d))
                    });
                    b();
                    (f = !1,
                    g !== l) || c(k)
                }
                ;var U = window.performance;
                function wa() {
                    if (google.c.c4t && U && U.mark && U.timing) {
                        var a = google.timers.load
                          , b = a.wsrt;
                        a = a.t.aft;
                        b && 0 < b && a && 0 < a && (a -= U.timing.navigationStart,
                        0 < a && (U.mark("SearchAFTStart", {
                            startTime: b
                        }),
                        U.mark("trigger:SearchAFTEnd", {
                            startTime: a
                        })))
                    }
                }
                ;var xa = !1, V = 0, W = 0, X = 0, Y = 0, Z;
                function ya(a, b) {
                    var c = google.c.wh
                      , d = !b;
                    b = b ? A(b) : -1;
                    var f = !X && !d && document.getElementById("rhs");
                    f ? (X = a,
                    Y = b,
                    I(function(e) {
                        e.D = !0
                    }, f)) : !W && (d || b >= c) && (W = a,
                    V = b);
                    if (d && W) {
                        var g = 0
                          , l = 0
                          , k = 0
                          , h = !1
                          , m = !1;
                        T(function(e) {
                            if (!(F(e) & 1))
                                return !1;
                            if (e.l)
                                return ++k,
                                !0;
                            F(e) & 4 && (e.D ? m = !0 : h = !0);
                            e.j && ++l;
                            ++g;
                            return !0
                        }, function() {
                            z("ima", g);
                            z("imad", l);
                            z("imac", k);
                            document.getElementsByClassName("Ib7Efc").length && z("ddl", 1);
                            z("wh", c)
                        }, function(e) {
                            e && y("afti", e);
                            0 < V && y("afts", W);
                            X && y("aftr", X);
                            var x = W
                              , Q = V;
                            if (X > x || ha && c && V < c && Y >= c)
                                x = X,
                                Q = Y;
                            e && (!ia || e > x || h && (!X || 0 > V) || m && (!fa || 0 < V)) && (x = e,
                            Q = c);
                            y("aft", x);
                            z("aft", 1);
                            z("aftp", Q);
                            va(function() {
                                Z && clearTimeout(Z);
                                ta("aft")
                            });
                            wa();
                            "hidden" === document.visibilityState && z("hddn", 1);
                            google.c.u("aft");
                            N(1)
                        })
                    }
                }
                ;function za(a, b) {
                    var c = 0;
                    T(function(d) {
                        (d = !d.l && (!!(F(d) & 1) || !!(F(d) & 4) && !(F(d) & 8) && !d.h)) && ++c;
                        return d
                    }, function() {
                        y("frts", a);
                        z("imf", c);
                        b && z("frtp", A(b))
                    }, function(d) {
                        y("frt", Math.max(d, a));
                        r && S();
                        q && google.c.u("frt");
                        N(2)
                    })
                }
                ;function Aa(a, b) {
                    T(function(c) {
                        return !!(F(c) & 1)
                    }, function() {
                        y("frts", a);
                        b && z("frtp", A(b))
                    }, function(c) {
                        y("frvt", Math.max(c, a));
                        S();
                        N(2)
                    })
                }
                ;var Ba = !1;
                google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight);
                var Ca = da || 0;
                if (0 < Ca)
                    a: {
                        if (window.performance && window.performance.timing && "navigationStart"in window.performance.timing) {
                            var Da = window.performance.now()
                              , Ea = Ca - Da;
                            if (0 < Ea) {
                                Z = setTimeout(ua, Ea, Math.floor(window.performance.timing.navigationStart + Da));
                                break a
                            }
                            ua()
                        }
                        Z = void 0
                    }
                google.c.maft = function(a, b) {
                    I(function() {});
                    xa || (google.c.b("aft"),
                    xa = !0);
                    ya(a, b)
                }
                ;
                google.c.mfrt = function(a, b) {
                    q && google.c.b("frt");
                    r && R.h++;
                    za(a, b)
                }
                ;
                google.c.mfrvt = function(a, b) {
                    R.h++;
                    Aa(a, b)
                }
                ;
                google.c.miml = function(a) {
                    function b(d) {
                        var f = F(d);
                        d.g.setAttribute("data-atf", String(f));
                        return w && !d.B && (!d.h || d.F || !!(F(d) & 1))
                    }
                    function c(d) {
                        w && y("iml", d || a);
                        google.c.u("iml")
                    }
                    Ba || (google.c.b("iml"),
                    function() {
                        T(b, function() {}, c)
                    }(0),
                    Ba = !0)
                }
                ;
                (u || v) && R.h++;
                google.c.ub = function() {
                    if (u || v)
                        S(),
                        google.c.ub = function() {}
                }
                ;
                google.c.setup = function(a) {
                    la(a);
                    return 0
                }
                ;
            }
            ).call(this);
            (function() {
                var b = [function() {
                    google.tick && google.tick("load", "dcl")
                }
                ];
                google.dclc = function(a) {
                    b.length ? b.push(a) : a()
                }
                ;
                function c() {
                    for (var a = b.shift(); a; )
                        a(),
                        a = b.shift()
                }
                window.addEventListener ? (document.addEventListener("DOMContentLoaded", c, !1),
                window.addEventListener("load", c, !1)) : window.attachEvent && window.attachEvent("onload", c);
            }
            ).call(this);
            (function() {
                var b = [];
                google.jsc = {
                    xx: b,
                    x: function(a) {
                        b.push(a)
                    },
                    mm: [],
                    m: function(a) {
                        google.jsc.mm.length || (google.jsc.mm = a)
                    }
                };
            }
            ).call(this);
            (function() {
                var e = this || self;
                var f = {};
                function x(a, c) {
                    if (null === c)
                        return !1;
                    if ("contains"in a && 1 == c.nodeType)
                        return a.contains(c);
                    if ("compareDocumentPosition"in a)
                        return a == c || !!(a.compareDocumentPosition(c) & 16);
                    for (; c && a != c; )
                        c = c.parentNode;
                    return c == a
                }
                ;var C = function(a, c) {
                    return function(d) {
                        d || (d = window.event);
                        return c.call(a, d)
                    }
                }
                  , D = "undefined" != typeof navigator && /Macintosh/.test(navigator.userAgent)
                  , E = function() {
                    this._mouseEventsPrevented = !0
                };
                var F = function(a) {
                    this.g = a;
                    this.h = []
                }
                  , G = function(a) {
                    for (var c = 0; c < a.h.length; ++c) {
                        var d = a.g
                          , b = a.h[c];
                        d.removeEventListener ? d.removeEventListener(b.eventType, b.s, b.capture) : d.detachEvent && d.detachEvent("on" + b.eventType, b.s)
                    }
                    a.h = []
                };
                var H = function() {
                    this.h = this.g = null
                }
                  , J = function(a, c) {
                    var d = I;
                    d.g = a;
                    d.h = c;
                    return d
                };
                H.prototype.i = function() {
                    var a = this.g;
                    this.g && this.g != this.h ? this.g = this.g.__owner || this.g.parentNode : this.g = null;
                    return a
                }
                ;
                var K = function() {
                    var a;
                    this.j = a = void 0 === a ? [] : a;
                    this.g = 0;
                    this.h = null;
                    this.l = !1
                }
                  , M = function(a, c) {
                    var d = L;
                    d.j = a;
                    d.g = 0;
                    d.h = c;
                    d.l = !1;
                    return d
                };
                K.prototype.i = function() {
                    if (this.l)
                        return I.i();
                    if (this.g != this.j.length) {
                        var a = this.j[this.g];
                        this.g++;
                        a != this.h && a && a.__owner && (this.l = !0,
                        J(a.__owner, this.h));
                        return a
                    }
                    return null
                }
                ;
                var I = new H
                  , L = new K;
                var P = function() {
                    this.v = [];
                    this.g = [];
                    this.h = [];
                    this.l = {};
                    this.i = null;
                    this.j = [];
                    O(this, "_custom")
                }
                  , Q = function(a) {
                    return String.prototype.trim ? a.trim() : a.replace(/^\s+/, "").replace(/\s+$/, "")
                }
                  , fa = function(a, c) {
                    return function m(b, g) {
                        g = void 0 === g ? !0 : g;
                        var l = c;
                        if ("_custom" == l) {
                            l = b.detail;
                            if (!l || !l._type)
                                return;
                            l = l._type
                        }
                        var k = l;
                        "click" == k && (D && b.metaKey || !D && b.ctrlKey || 2 == b.which || null == b.which && 4 == b.button || b.shiftKey) ? k = "clickmod" : "keydown" == k && !b.a11ysc && (k = "maybe_click");
                        var u = b.srcElement || b.target;
                        l = R(k, b, u, "", null);
                        var Z = b.path ? M(b.path, this) : b.composedPath ? M(b.composedPath(), this) : J(u, this);
                        for (var p; p = Z.i(); ) {
                            var h = p;
                            var q = void 0;
                            var r = h;
                            p = k;
                            var n = r.__jsaction;
                            if (!n) {
                                var w;
                                n = null;
                                "getAttribute"in r && (n = r.getAttribute("jsaction"));
                                if (w = n) {
                                    n = f[w];
                                    if (!n) {
                                        n = {};
                                        for (var y = w.split(aa), ba = y ? y.length : 0, z = 0; z < ba; z++) {
                                            var v = y[z];
                                            if (v) {
                                                var A = v.indexOf(":")
                                                  , N = -1 != A
                                                  , da = N ? Q(v.substr(0, A)) : ca;
                                                v = N ? Q(v.substr(A + 1)) : v;
                                                n[da] = v
                                            }
                                        }
                                        f[w] = n
                                    }
                                    r.__jsaction = n
                                } else
                                    n = ea,
                                    r.__jsaction = n
                            }
                            r = n;
                            "maybe_click" == p && r.click ? (q = p,
                            p = "click") : "clickkey" == p ? p = "click" : "click" != p || r.click || (p = "clickonly");
                            q = {
                                eventType: q ? q : p,
                                action: r[p] || "",
                                event: null,
                                ignore: !1
                            };
                            l = R(q.eventType, q.event || b, u, q.action || "", h, l.timeStamp);
                            if (q.ignore || q.action)
                                break
                        }
                        l && "touchend" == l.eventType && (l.event._preventMouseEvents = E);
                        if (q && q.action) {
                            if ("mouseenter" == k || "mouseleave" == k || "pointerenter" == k || "pointerleave" == k)
                                if (u = b.relatedTarget,
                                !("mouseover" == b.type && "mouseenter" == k || "mouseout" == b.type && "mouseleave" == k || "pointerover" == b.type && "pointerenter" == k || "pointerout" == b.type && "pointerleave" == k) || u && (u === h || x(h, u)))
                                    l.action = "",
                                    l.actionElement = null;
                                else {
                                    k = {};
                                    for (var t in b)
                                        "function" !== typeof b[t] && "srcElement" !== t && "target" !== t && (k[t] = b[t]);
                                    k.type = "mouseover" == b.type ? "mouseenter" : "mouseout" == b.type ? "mouseleave" : "pointerover" == b.type ? "pointerenter" : "pointerleave";
                                    k.target = k.srcElement = h;
                                    k.bubbles = !1;
                                    l.event = k;
                                    l.targetElement = h
                                }
                        } else
                            l.action = "",
                            l.actionElement = null;
                        h = l;
                        a.i && !h.event.a11ysgd && (t = R(h.eventType, h.event, h.targetElement, h.action, h.actionElement, h.timeStamp),
                        "clickonly" == t.eventType && (t.eventType = "click"),
                        a.i(t, !0));
                        if (h.actionElement || "maybe_click" == h.eventType)
                            if (a.i)
                                !h.actionElement || "A" != h.actionElement.tagName || "click" != h.eventType && "clickmod" != h.eventType || (b.preventDefault ? b.preventDefault() : b.returnValue = !1),
                                (b = a.i(h)) && g && m.call(this, b, !1);
                            else {
                                if ((g = e.document) && !g.createEvent && g.createEventObject)
                                    try {
                                        var B = g.createEventObject(b)
                                    } catch (ja) {
                                        B = b
                                    }
                                else
                                    B = b;
                                h.event = B;
                                a.j.push(h)
                            }
                    }
                }
                  , R = function(a, c, d, b, g, m) {
                    return {
                        eventType: a,
                        event: c,
                        targetElement: d,
                        action: b,
                        actionElement: g,
                        timeStamp: m || Date.now()
                    }
                }
                  , ha = function(a, c) {
                    return function(d) {
                        var b = a
                          , g = c
                          , m = !1;
                        "mouseenter" == b ? b = "mouseover" : "mouseleave" == b ? b = "mouseout" : "pointerenter" == b ? b = "pointerover" : "pointerleave" == b && (b = "pointerout");
                        if (d.addEventListener) {
                            if ("focus" == b || "blur" == b || "error" == b || "load" == b || "toggle" == b)
                                m = !0;
                            d.addEventListener(b, g, m)
                        } else
                            d.attachEvent && ("focus" == b ? b = "focusin" : "blur" == b && (b = "focusout"),
                            g = C(d, g),
                            d.attachEvent("on" + b, g));
                        return {
                            eventType: b,
                            s: g,
                            capture: m
                        }
                    }
                }
                  , O = function(a, c) {
                    if (!a.l.hasOwnProperty(c)) {
                        var d = fa(a, c)
                          , b = ha(c, d);
                        a.l[c] = d;
                        a.v.push(b);
                        for (d = 0; d < a.g.length; ++d) {
                            var g = a.g[d];
                            g.h.push(b.call(null, g.g))
                        }
                        "click" == c && O(a, "keydown")
                    }
                };
                P.prototype.s = function(a) {
                    return this.l[a]
                }
                ;
                var V = function(a, c) {
                    var d = new F(c);
                    a: {
                        for (var b = 0; b < a.g.length; b++)
                            if (S(a.g[b].g, c)) {
                                c = !0;
                                break a
                            }
                        c = !1
                    }
                    if (c)
                        return a.h.push(d),
                        d;
                    T(a, d);
                    a.g.push(d);
                    U(a);
                    return d
                }
                  , U = function(a) {
                    for (var c = a.h.concat(a.g), d = [], b = [], g = 0; g < a.g.length; ++g) {
                        var m = a.g[g];
                        W(m, c) ? (d.push(m),
                        G(m)) : b.push(m)
                    }
                    for (g = 0; g < a.h.length; ++g)
                        m = a.h[g],
                        W(m, c) ? d.push(m) : (b.push(m),
                        T(a, m));
                    a.g = b;
                    a.h = d
                }
                  , T = function(a, c) {
                    var d = c.g;
                    ia && (d.style.cursor = "pointer");
                    for (d = 0; d < a.v.length; ++d)
                        c.h.push(a.v[d].call(null, c.g))
                }
                  , X = function(a, c) {
                    a.i = c;
                    a.j && (0 < a.j.length && c(a.j),
                    a.j = null)
                }
                  , W = function(a, c) {
                    for (var d = 0; d < c.length; ++d)
                        if (c[d].g != a.g && S(c[d].g, a.g))
                            return !0;
                    return !1
                }
                  , S = function(a, c) {
                    for (; a != c && c.parentNode; )
                        c = c.parentNode;
                    return a == c
                }
                  , ia = "undefined" != typeof navigator && /iPhone|iPad|iPod/.test(navigator.userAgent)
                  , aa = /\s*;\s*/
                  , ca = "click"
                  , ea = {};
                var Y = new P;
                V(Y, window.document.documentElement);
                O(Y, "click");
                O(Y, "focus");
                O(Y, "focusin");
                O(Y, "blur");
                O(Y, "focusout");
                O(Y, "error");
                O(Y, "load");
                O(Y, "auxclick");
                O(Y, "change");
                O(Y, "copy");
                O(Y, "dblclick");
                O(Y, "beforeinput");
                O(Y, "input");
                O(Y, "keyup");
                O(Y, "keydown");
                O(Y, "keypress");
                O(Y, "mousedown");
                O(Y, "mouseenter");
                O(Y, "mouseleave");
                O(Y, "mouseout");
                O(Y, "mouseover");
                O(Y, "mouseup");
                O(Y, "paste");
                O(Y, "pointerenter");
                O(Y, "pointerleave");
                O(Y, "touchstart");
                O(Y, "touchmove");
                O(Y, "touchend");
                O(Y, "touchcancel");
                O(Y, "transitioncancel");
                O(Y, "transitionend");
                O(Y, "transitionrun");
                O(Y, "transitionstart");
                O(Y, "dragover");
                O(Y, "dragenter");
                O(Y, "dragleave");
                O(Y, "drop");
                O(Y, "dragstart");
                O(Y, "dragend");
                O(Y, "speech");
                (function(a) {
                    google.jsad = function(c) {
                        X(a, c)
                    }
                    ;
                    google.jsaac = function(c) {
                        return V(a, c)
                    }
                    ;
                    google.jsarc = function(c) {
                        G(c);
                        for (var d = !1, b = 0; b < a.g.length; ++b)
                            if (a.g[b] === c) {
                                a.g.splice(b, 1);
                                d = !0;
                                break
                            }
                        if (!d)
                            for (d = 0; d < a.h.length; ++d)
                                if (a.h[d] === c) {
                                    a.h.splice(d, 1);
                                    break
                                }
                        U(a)
                    }
                }
                )(Y);
                e.gws_wizbind = function(a) {
                    return {
                        trigger: function(c) {
                            var d = a.s(c.type);
                            d || (O(a, c.type),
                            d = a.s(c.type));
                            var b = c.target || c.srcElement;
                            d && d.call(b.ownerDocument.documentElement, c)
                        },
                        bind: function(c) {
                            X(a, c)
                        }
                    }
                }(Y);
            }
            ).call(this);
            (function() {
                window.google.erd = {
                    jsr: 1,
                    bv: 1919,
                    sd: true,
                    de: true
                };
            }
            )();
            (function() {
                var sdo = false;
                var mei = 10;
                var h = this || self;
                var k, l = null != (k = h.mei) ? k : 1, n, p = null != (n = h.sdo) ? n : !0, q = 0, r, t = google.erd, v = t.jsr;
                google.ml = function(a, b, d, m, e) {
                    e = void 0 === e ? 2 : e;
                    b && (r = a && a.message);
                    void 0 === d && (d = {});
                    d.cad = "ple_" + google.ple + ".aple_" + google.aple;
                    if (google.dl)
                        return google.dl(a, e, d),
                        null;
                    if (0 > v) {
                        window.console && console.error(a, d);
                        if (-2 === v)
                            throw a;
                        b = !1
                    } else
                        b = !a || !a.message || "Error loading script" === a.message || q >= l && !m ? !1 : !0;
                    if (!b)
                        return null;
                    q++;
                    d = d || {};
                    b = encodeURIComponent;
                    var c = "/gen_204?atyp=i&ei=" + b(google.kEI);
                    google.kEXPI && (c += "&jexpid=" + b(google.kEXPI));
                    c += "&srcpg=" + b(google.sn) + "&jsr=" + b(t.jsr) + "&bver=" + b(t.bv);
                    var f = a.lineNumber;
                    void 0 !== f && (c += "&line=" + f);
                    var g = a.fileName;
                    g && (0 < g.indexOf("-extension:/") && (e = 3),
                    c += "&script=" + b(g),
                    f && g === window.location.href && (f = document.documentElement.outerHTML.split("\n")[f],
                    c += "&cad=" + b(f ? f.substring(0, 300) : "No script found.")));
                    google.ple && 1 === google.ple && (e = 2);
                    c += "&jsel=" + e;
                    for (var u in d)
                        c += "&",
                        c += b(u),
                        c += "=",
                        c += b(d[u]);
                    c = c + "&emsg=" + b(a.name + ": " + a.message);
                    c = c + "&jsst=" + b(a.stack || "N/A");
                    12288 <= c.length && (c = c.substr(0, 12288));
                    a = c;
                    m || google.log(0, "", a);
                    return a
                }
                ;
                window.onerror = function(a, b, d, m, e) {
                    r !== a && (a = e instanceof Error ? e : Error(a),
                    void 0 === d || "lineNumber"in a || (a.lineNumber = d),
                    void 0 === b || "fileName"in a || (a.fileName = b),
                    google.ml(a, !1, void 0, !1, "SyntaxError" === a.name || "SyntaxError" === a.message.substring(0, 11) || -1 !== a.message.indexOf("Script error") ? 3 : 0));
                    r = null;
                    p && q >= l && (window.onerror = null)
                }
                ;
            }
            )();
            var h = "function" == typeof Object.defineProperties ? Object.defineProperty : function(a, b, c) {
                if (a == Array.prototype || a == Object.prototype)
                    return a;
                a[b] = c.value;
                return a
            }
              , k = function(a) {
                a = ["object" == typeof globalThis && globalThis, a, "object" == typeof window && window, "object" == typeof self && self, "object" == typeof global && global];
                for (var b = 0; b < a.length; ++b) {
                    var c = a[b];
                    if (c && c.Math == Math)
                        return c
                }
                throw Error("a");
            }
              , l = k(this)
              , m = function(a, b) {
                if (b)
                    a: {
                        var c = l;
                        a = a.split(".");
                        for (var d = 0; d < a.length - 1; d++) {
                            var e = a[d];
                            if (!(e in c))
                                break a;
                            c = c[e]
                        }
                        a = a[a.length - 1];
                        d = c[a];
                        b = b(d);
                        b != d && null != b && h(c, a, {
                            configurable: !0,
                            writable: !0,
                            value: b
                        })
                    }
            };
            m("String.prototype.startsWith", function(a) {
                return a ? a : function(b, c) {
                    if (null == this)
                        throw new TypeError("The 'this' value for String.prototype.startsWith must not be null or undefined");
                    if (b instanceof RegExp)
                        throw new TypeError("First argument to String.prototype.startsWith must not be a regular expression");
                    var d = this + "";
                    b += "";
                    var e = d.length
                      , g = b.length;
                    c = Math.max(0, Math.min(c | 0, d.length));
                    for (var f = 0; f < g && c < e; )
                        if (d[c++] != b[f++])
                            return !1;
                    return f >= g
                }
            });
            google.arwt = function(a) {
                a.href = document.getElementById(a.id.substring(a.id.startsWith("vcs") ? 3 : 1)).href;
                return !0
            }
            ;
            (function() {
                google.eufsv = true;
                (function() {
                    var f = function(a) {
                        var b = a.url;
                        a = a.j;
                        this.h = b;
                        this.l = a;
                        a = /[?&]dsh=1(&|$)/.test(b);
                        this.i = !a && /[?&]ae=1(&|$)/.test(b);
                        this.v = !a && /[?&]ae=2(&|$)/.test(b);
                        if ((this.g = /[?&]adurl=([^&]*)/.exec(b)) && this.g[1]) {
                            try {
                                var d = decodeURIComponent(this.g[1])
                            } catch (c) {
                                d = null
                            }
                            this.s = d
                        }
                    }
                      , k = function(a, b) {
                        return a.i && a.s || a.v ? 1 == b ? a.i ? a.s : h(a, "&dct=1") : 2 == b ? h(a, "&ri=2") : h(a, "&ri=16") : a.h
                    }
                      , h = function(a, b) {
                        return a.g ? a.h.slice(0, a.g.index) + b + a.h.slice(a.g.index) : a.h + b
                    }
                      , m = function(a) {
                        a = a.l;
                        var b = encodeURIComponent
                          , d = "";
                        a.platform && (d += "&uap=" + b(a.platform));
                        a.platformVersion && (d += "&uapv=" + b(a.platformVersion));
                        a.uaFullVersion && (d += "&uafv=" + b(a.uaFullVersion));
                        a.architecture && (d += "&uaa=" + b(a.architecture));
                        a.model && (d += "&uam=" + b(a.model));
                        a.bitness && (d += "&uab=" + b(a.bitness));
                        a.fullVersionList && (d += "&uafvl=" + b(a.fullVersionList.map(function(c) {
                            return b(c.brand) + ";" + b(c.version)
                        }).join("|")));
                        "undefined" !== typeof a.wow64 && (d += "&uaw=" + Number(a.wow64));
                        return d
                    };
                    var n = function(a) {
                        this.g = a
                    };
                    n.prototype.toString = function() {
                        return this.g.toString()
                    }
                    ;
                    var p = function(a) {
                        return a instanceof n && a.constructor === n ? a.g : "type_error:SafeUrl"
                    }
                      , q = {}
                      , r = new n("about:invalid#zClosurez",q);
                    var t = function(a) {
                        this.B = a
                    };
                    function u(a) {
                        return new t(function(b) {
                            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
                        }
                        )
                    }
                    var v = [u("data"), u("http"), u("https"), u("mailto"), u("ftp"), new t(function(a) {
                        return /^[^:]*([/?#]|$)/.test(a)
                    }
                    )]
                      , w = "function" === typeof URL;
                    function x(a) {
                        a: if (w) {
                            try {
                                var b = new URL(a)
                            } catch (d) {
                                b = "https:";
                                break a
                            }
                            b = b.protocol
                        } else
                            b: {
                                b = document.createElement("a");
                                try {
                                    b.href = a
                                } catch (d) {
                                    b = void 0;
                                    break b
                                }
                                b = b.protocol;
                                b = ":" === b || "" === b ? "https:" : b
                            }
                        if ("javascript:" !== b)
                            return a
                    }
                    ;var y = /^((market|itms|intent|itms-appss):\/\/)/i;
                    var z = function() {
                        var a = {
                            A: google.eufsv
                        }
                          , b = this;
                        a = (void 0 === a ? {} : a).A;
                        this.g = null;
                        a && navigator.userAgentData && navigator.userAgentData.getHighEntropyValues && (a = navigator.userAgentData.getHighEntropyValues("platform platformVersion uaFullVersion architecture model bitness fullVersionList wow64".split(" "))) && a.then(function(d) {
                            b.g = d
                        })
                    };
                    z.prototype.handle = function(a) {
                        if (a.hasAttribute("data-ohref"))
                            var b = a.getAttribute("data-ohref");
                        else
                            b = a.href,
                            a.setAttribute("data-ohref", b);
                        var d = b;
                        var c = {
                            j: this.g
                        };
                        c = new f({
                            url: d,
                            j: (void 0 === c ? {} : c).j
                        });
                        if (c.i && c.s || c.v)
                            if (navigator.sendBeacon) {
                                d = navigator;
                                var g = d.sendBeacon
                                  , l = "&act=1&ri=1";
                                c.i && c.l && (l += m(c));
                                c = g.call(d, h(c, l), "") ? k(c, 1) : k(c, 2)
                            } else
                                c = k(c, 0);
                        else
                            c = d;
                        c = c instanceof n || !y.test(c) ? c : new n(c,q);
                        b != c && (b = c instanceof n ? p(c) : x(c),
                        void 0 !== b && (a.href = b))
                    }
                    ;
                    function B(a, b) {
                        var d = /[?&]adurl=/.exec(b);
                        return d ? "" + b.slice(0, d.index + 1) + a + "&" + b.slice(d.index + 1) : "" + b + (-1 === b.indexOf("?") ? "?" : "&") + a
                    }
                    function C(a, b) {
                        a = a.href;
                        var d = /[?&]nis=([^&]*)/.exec(a);
                        return d && d[1] === b ? a : d ? a.replace(/([?&])nis=([^&]*)/, function(c, g) {
                            return g + "nis=" + b
                        }) : B("nis=" + b, a)
                    }
                    function D() {
                        var a;
                        return !(null == (a = document.featurePolicy) || !a.allowedFeatures().includes("attribution-reporting"))
                    }
                    ;function E(a) {
                        a && -1 != a.indexOf("&sph") && (google.cufph = -1 != a.indexOf("ctype=") ? a.replace(/(.*ctype=)(\d+)(.*)/, "$1331$3") : a + "&ctype=331",
                        google.vcmd = "clicked")
                    }
                    ;var F = new z;
                    google.ausb = function(a) {
                        if (!a)
                            return google.ml(Error("a"), !1),
                            !0;
                        if (a.hasAttribute("data-impdclcc"))
                            try {
                                var b = a.hasAttribute("attributionsourceid") && a.hasAttribute("attributiondestination") ? "2" : a.hasAttribute("attributionsrc") ? D() ? "6" : "5" : D() ? "7" : "8";
                                var d = C(a, b);
                                var c = void 0 === c ? v : c;
                                a: if (b = c,
                                b = void 0 === b ? v : b,
                                d instanceof n)
                                    var g = d;
                                else {
                                    for (c = 0; c < b.length; ++c) {
                                        var l = b[c];
                                        if (l instanceof t && l.B(d)) {
                                            g = new n(d,q);
                                            break a
                                        }
                                    }
                                    g = void 0
                                }
                                var e = g || r;
                                var A = e instanceof n ? p(e) : x(e);
                                void 0 !== A && (a.href = A)
                            } catch (G) {}
                        a.getAttribute("data-sbv2") && ((google.eplfdd || google.ellfdd) && "_blank" !== a.target && (google.iutaicc ? (e = a.hasAttribute("data-ohref") ? a.getAttribute("data-ohref") : a.href,
                        e = new f({
                            url: e,
                            j: F.g
                        }),
                        e = e.l ? h(e, m(e)) : e.h,
                        E(e)) : (e = a.hasAttribute("data-ohref") ? a.getAttribute("data-ohref") : a.href,
                        E(e))),
                        F.handle(a));
                        return !0
                    }
                    ;
                }
                ).call(this);
            }
            )();
            (function() {
                var f = function(a) {
                    var b = 0;
                    return function() {
                        return b < a.length ? {
                            done: !1,
                            value: a[b++]
                        } : {
                            done: !0
                        }
                    }
                };
                var g = this || self;
                var h = function(a, b) {
                    if (b = "label" + (null != b ? "=" + encodeURIComponent(String(b)) : "")) {
                        var c = a.indexOf("#");
                        0 > c && (c = a.length);
                        var d = a.indexOf("?");
                        if (0 > d || d > c) {
                            d = c;
                            var e = ""
                        } else
                            e = a.substring(d + 1, c);
                        a = [a.slice(0, d), e, a.slice(c)];
                        c = a[1];
                        a[1] = b ? c ? c + "&" + b : b : c;
                        b = a[0] + (a[1] ? "?" + a[1] : "") + a[2]
                    } else
                        b = a;
                    return b
                };
                function k(a) {
                    for (; a && a != document.documentElement; a = a.parentElement)
                        if ("A" == a.tagName)
                            return a;
                    return null
                }
                function l() {
                    if ("visible" === document.visibilityState)
                        google.ellfdd && m(),
                        google.vcmd = "",
                        google.cufph = "";
                    else if ("hidden" === document.visibilityState && google.cufph && google.vcmd) {
                        if (google.ellfdd)
                            try {
                                var a = JSON.parse(window.localStorage.getItem("uha") || "[]");
                                a.push(google.cufph + "," + google.vcmd);
                                window.localStorage.setItem("uha", JSON.stringify(a))
                            } catch (b) {
                                navigator && null != navigator.sendBeacon && navigator.sendBeacon(h(google.cufph, -1 != google.vcmd.indexOf("pagehide") ? "hph_v2" : "noph_v2"))
                            }
                        google.eplfdd && navigator && null != navigator.sendBeacon && navigator.sendBeacon(h(google.cufph, -1 != google.vcmd.indexOf("pagehide") ? "hph" : "noph"))
                    }
                }
                function n() {
                    google.cufph && google.vcmd && (google.vcmd += "+pagehide")
                }
                function p() {
                    m()
                }
                function m() {
                    try {
                        var a = JSON.parse(window.localStorage.getItem("uha") || "[]");
                        if (0 !== a.length) {
                            if (navigator && null != navigator.sendBeacon)
                                for (var b = 0; b < a.length; b++) {
                                    var c = a[b].split(",");
                                    if (2 === c.length) {
                                        var d = "undefined" != typeof Symbol && Symbol.iterator && c[Symbol.iterator];
                                        if (d)
                                            var e = d.call(c);
                                        else if ("number" == typeof c.length)
                                            e = {
                                                next: f(c)
                                            };
                                        else
                                            throw Error("a`" + String(c));
                                        var r = e.next().value
                                          , t = e.next().value;
                                        navigator.sendBeacon(h(r, -1 != t.indexOf("pagehide") ? "hph_v2" : "noph_v2"))
                                    }
                                }
                            window.localStorage.removeItem("uha")
                        }
                    } catch (v) {}
                }
                function q(a) {
                    if (a = k(a.target))
                        switch (a.getAttribute("data-agdh")) {
                        case "arwt":
                            google.arwt(a);
                            break;
                        case "fvd3vc":
                            g.J4LCUe(a);
                            break;
                        case "EdKoMd":
                            (0,
                            google.f.LmvwCb)(a)
                        }
                    return !0
                }
                function u(a) {
                    return "Enter" === a.key ? q(a) : !0
                }
                ;window.document.documentElement.addEventListener("mousedown", q, !0);
                window.document.documentElement.addEventListener("touchstart", q, !0);
                google.iokefur && window.document.documentElement.addEventListener("keydown", u, !0);
                window.document.documentElement.addEventListener("click", function(a) {
                    var b = k(a.target);
                    if (b)
                        switch (b.getAttribute("data-agch")) {
                        case "ausb":
                            google.ausb(b);
                            break;
                        case "HJ3bqe":
                            window.YvikHb(a, b);
                            break;
                        case "cqUJI":
                            (0,
                            google.f.DfwaCb)(b)
                        }
                    return !0
                }, !0);
                google.eplfdd && google.ellfdd ? (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0),
                window.addEventListener("load", p, !0)) : google.eplfdd ? (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0)) : google.ellfdd && (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0),
                window.addEventListener("load", p, !0));
            }
            ).call(this);
            /*CSH_START*/
            /*CSH_END*/
        </script>
        <style>
            html,body,h1,input,select {
                font-family: arial,sans-serif
            }

            html {
                filter: none
            }

            body.srp,body {
                background: #202124
            }

            img,[role=img],video,iframe {
                filter: none
            }

            body,h1 {
                font-size: 14px;
            }

            h1 {
                font-weight: normal;
                margin: 0;
                padding: 0
            }

            h3 {
                font-weight: normal;
                margin: 0;
                padding: 0;
                font-size: 20px;
                line-height: 1.3
            }

            body {
                margin: 0;
                color: #bdc1c6;
            }

            a {
                color: #8ab4f8;
                text-decoration: none;
                -webkit-tap-highlight-color: rgba(255,255,255,.1)
            }

            a:visited {
                color: #c58af9
            }

            a:hover {
                text-decoration: underline
            }

            a:hover h3 {
                text-decoration: underline
            }

            a.a-no-hover-decoration:hover,a.a-no-hover-decoration:hover h3 {
                text-decoration: none
            }

            cite,cite a:link,cite a:visited {
                color: #bdc1c6;
                font-style: normal
            }

            button {
                margin: 0
            }

            ol li {
                list-style: none
            }

            ol,ul,li {
                margin: 0;
                padding: 0
            }

            input {
                font-size: 14px
            }

            em {
                font-weight: bold;
                font-style: normal
            }

            .aCOpRe em,.yXK7lf em {
                color: #bcc0c3;
            }

            .aCOpRe a em {
                color: inherit
            }

            @-webkit-keyframes qs-timer {
                0% {
                }
            }

            html:not(.zAoYTe) [tabindex],html:not(.zAoYTe) [href],html:not(.zAoYTe) button,html:not(.zAoYTe) iframe,html:not(.zAoYTe) input,html:not(.zAoYTe) select,html:not(.zAoYTe) textarea,html:not(.zAoYTe) .F0azHf {
                outline: 0
            }

            .z1asCe {
                display: inline-block;
                fill: currentColor;
                height: 24px;
                line-height: 24px;
                position: relative;
                width: 24px
            }

            .z1asCe svg {
                display: block;
                height: 100%;
                width: 100%
            }

            :root {
            }

            .ynAwRc {
                color: #8ab4f8
            }

            a:visited .ynAwRc,a:visited.ynAwRc {
                color: #c58af9;
            }

            .JIFdL {
                color: #8ab4f8
            }

            .zIamNc {
                color: #bdc1c6;
                font-family: arial,sans-serif;
                font-size: 12px;
                font-weight: 400;
                line-height: 20px
            }

            .NUnG9d {
                color: #bdc1c6;
                font-family: arial,sans-serif;
                font-size: 12px;
                font-weight: 400;
                line-height: 16px
            }

            .kqEaA {
                color: #9aa0a6;
                font-family: arial,sans-serif;
                font-size: 14px;
                font-weight: 400;
                line-height: 22px
            }

            .vJtJab {
                color: #8ab4f8;
                font-family: arial,sans-serif;
                font-size: 14px;
                font-weight: 400;
                line-height: 22px
            }

            .hWgrdb {
                font-style: italic
            }

            .Z5bgrc {
                font-family: arial,sans-serif-medium,sans-serif;
                font-weight: 500
            }

            .l97dzf {
                font-weight: 400
            }

            .N8MDs {
                font-family: arial,sans-serif-light,sans-serif
            }

            .z8gr9e {
                color: #bdc1c6
            }

            .KHW3x {
                color: #202124
            }

            .ZYHQ7e {
                color: #9aa0a6
            }

            .x2sBq {
                color: #f28b82
            }

            .tGXccd {
                color: #81c995
            }

            .OvuNCb {
                color: #fdd663
            }

            .yNSCTe {
                color: #bdc1c6
            }

            .XEI2lf {
                color: #fff
            }

            .u2fAP {
                color: #3c4043
            }

            .Q7PwXb {
                text-decoration: none
            }

            .NyOyWb {
                text-overflow: clip;
                overflow: hidden
            }

            .U2GSdd {
                height: calc(16px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .GnYZ5c {
                height: calc(16px*3);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 3;
                overflow: hidden;
                white-space: normal
            }

            .potOpf {
                max-height: calc(24px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .n4krj {
                height: calc(22px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .NnEaBd {
                text-align: right
            }

            .xLQxIf {
                text-transform: capitalize
            }

            .uKdaQe {
                text-transform: lowercase
            }

            .MUmB9 {
                text-transform: none
            }

            .iUh30 {
                font-size: 12px;
                line-height: 1.3
            }

            .f {
                color: #9aa0a6;
                line-height: 1.58
            }

            .g {
                font-family: arial,sans-serif;
                font-size: 14px;
            }

            .g {
                line-height: 1.58;
                text-align: left
            }

            .g {
                width: 600px;
                margin-top: 0;
                margin-bottom: 30px;
            }

            .iUh30 {
                padding-top: 1px;
            }

            .vk_arc {
                border-top: 1px solid #3c4043;
                cursor: pointer;
                height: 0;
                margin-bottom: -19px;
                overflow: hidden;
                padding: 20px 0;
                text-align: center
            }

            .vk_ard {
                top: -11px
            }

            .vk_aru {
                bottom: -6px
            }

            .vk_ard,.vk_aru {
                background-color: #b8bbbe;
                margin-left: auto;
                margin-right: auto;
                position: relative;
                height: 6px;
                width: 64px
            }

            .vk_ard:after,.vk_ard:before,.vk_aru:after,.vk_aru:before {
                content: ' ';
                height: 0;
                left: 0;
                position: absolute;
                width: 0;
                border-left: 32px solid rgba(0,0,0,0);
                border-right: 32px solid rgba(0,0,0,0)
            }

            .vk_ard:before {
                border-top: 16px solid #b8bbbe;
                top: 6px
            }

            .vk_aru:before {
                border-bottom: 16px solid #b8bbbe;
                bottom: 6px
            }

            .vk_ard:after {
                top: 0;
                border-top: 16px solid #202124
            }

            .vk_aru:after {
                bottom: 0;
                border-bottom: 16px solid #202124
            }

            .jC7Epd.vk_ard,.jC7Epd.vk_aru {
                background-color: #202124
            }

            .jC7Epd.vk_ard:before {
                border-top-color: #dddee1
            }

            .jC7Epd.vk_aru:before {
                border-bottom-color: #dddee1
            }

            .xpdclps,.xpdxpnd {
                overflow: hidden
            }

            .xpdclps,.xpdxpnd {
                -webkit-transition: max-height 0.3s
            }

            .xpdxpnd,.xpdopen .xpdclps,.xpdopen .xpdxpnd.xpdnoxpnd {
                max-height: 0
            }

            .xpdopen .xpdxpnd {
                max-height: none
            }

            .xpdopen .xpdbox .xpdxpnd,.xpdopen .xpdbox.xpdopen .xpdclps {
                max-height: 0
            }

            .xpdopen .xpdbox.xpdopen .xpdxpnd,.xpdopen .xpdbox .xpdclps {
                max-height: none
            }

            .xpdclose .k5nfEc {
                display: none
            }

            .fp-i .SzDvzc {
                display: none
            }

            .fp-f {
                bottom: 0;
                height: auto;
                left: 0;
                position: fixed !important;
                right: 0;
                top: 0;
                width: auto;
                z-index: 127
            }

            .fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
                display: none !important
            }

            .fp-zh.fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
                display: block !important;
                height: 0;
                overflow: hidden;
                transform: translate3d(0,0,0);
                transform: translate3d(0,0,0)
            }

            .fp-i .fp-c {
                display: block;
                min-height: 100vh
            }

            li.fp-c {
                list-style: none
            }

            .fp-w {
                box-sizing: border-box;
                left: 0;
                margin-left: auto;
                margin-right: auto;
                max-width: 1217px;
                right: 0
            }

            .ellip {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap
            }

            .tF2Cxc {
                position: relative
            }

            .Jb0Zif .BDNLRc {
                margin: 16px 16px -11px
            }

            .RUXr2d {
                display: inline
            }

            .MTB56 {
                padding: 0px;
                border-radius: 0px;
                background-color: #fff;
                margin-right: 12px;
                vertical-align: middle
            }

            .Pthbuf {
                display: flex;
                align-items: center
            }

            .m164Nd {
                vertical-align: middle;
                display: inline-block
            }

            .qpGQpf {
                clear: both;
                padding-top: 6px
            }

            .tcPEUc .MTB56 {
                display: none
            }

            .aCOpRe {
                line-height: 1.58;
                word-wrap: break-word
            }

            .aCOpRe sup {
                line-height: 0.9
            }

            .yuRUbf {
                font-weight: normal;
                font-size: small;
                line-height: 1.58;
            }

            .IsZvec {
                max-width: 48em;
                color: #bdc1c6;
                line-height: 1.58
            }

            .uo4vr {
                color: #9aa0a6;
                line-height: 1.58
            }

            .IjZ7ze {
                display: inline-block;
                color: #9aa0a6;
                font-size: 12px;
                line-height: 1.34;
                white-space: nowrap
            }

            .FyYA1e {
                margin: 5px 0
            }

            .P1usbc {
                display: table;
                white-space: nowrap;
                margin: 5px 0;
                line-height: 1.58;
                color: #9aa0a6;
            }

            .G1Rrjc {
                display: table-cell;
                padding-left: 15px;
                vertical-align: baseline
            }

            .i4vd5e {
                display: table-cell
            }

            .VNLkW {
                display: table-row;
                vertical-align: top
            }

            .h7mcFf {
                color: #9aa0a6
            }

            .k6DEPe {
                display: table-row;
                width: 100%
            }

            .TXwUJf {
                color: #9aa0a6
            }

            .PcHvNb {
                position: absolute
            }

            .N3nEGc {
                background-color: #202124;
                float: left;
                margin-top: 4px
            }

            .wEQKyf.N3nEGc {
                float: right;
                margin: 7px 0 5px 12px
            }

            .wEQKyf.Ik9SRc.N3nEGc {
                margin: 2px 0 0 0
            }

            .Ixi80c {
                margin-top: 0
            }

            .i0PvJb {
                background-color: #fff
            }

            .mWTy7c {
                border-top-left-radius: 2px;
                bottom: 0;
                font-size: 11px;
                padding: 1px 3px;
                position: absolute;
                right: 0;
                background-color: rgba(255,255,255,.7);
                color: #202124
            }

            .rGhul {
                display: block;
                position: relative;
                overflow: hidden
            }

            .rGhul:focus {
                outline-style: solid;
                outline-width: 2px
            }

            .vYWbhc {
                margin-top: 0
            }

            .TbwUpd a.fl {
                font-size: 12px
            }

            .TQc1id .qLRx3b {
                font-size: 14px;
                line-height: 1.58
            }

            .TbwUpd {
                display: inline-block;
                padding-bottom: 2px;
                padding-top: 1px;
                -webkit-text-size-adjust: none
            }

            .NJjxre {
                position: absolute;
                left: 0;
                top: 0
            }

            .M8OgIe .VWCdhc.Mjve0e .TbwUpd {
                width: max-content
            }

            #rhs {
                margin-left: var(--rhs-margin);
                flex: 0 auto;
                width: var(--rhs-width);
                position: relative;
                padding-bottom: 15px;
                transition: opacity 0.3s
            }

            #rhs .scrt.VjDLd,#rhs table.VjDLd {
                border: 0
            }

            #rhs .VjDLd {
                border: 1px solid #050607;
                padding-left: 17px;
                padding-right: 16px;
                position: relative;
                box-sizing: border-box
            }

            .s6JM6d .SwlyWb {
                display: none
            }

            #rhs.rhstc4 .VjDLd {
                width: var(--rhs-width);
            }

            #rhs.rhstc5 .VjDLd {
                width: 457px
            }

            .rhstc4 .nmrhhd {
                background: none !important;
                display: none !important
            }

            .rhstc5 .SwlyWb {
                background: none !important;
                display: none !important
            }

            .GLcBOb {
                color: #9aa0a6;
                font-size: 14px;
                font-family: Google Sans,arial,sans-serif;
                border-bottom: 1px solid #3c4043;
                position: relative;
                z-index: 126
            }

            .IC1Ck {
                position: relative;
                white-space: nowrap;
                align-items: baseline;
                display: flex;
                -ms-flex-pack: justify;
                float: left;
                justify-content: space-between;
                min-width: calc(var(--center-abs-margin) + 652px);
            }

            .MUFPAc {
                display: inline;
                margin-left: calc(var(--center-abs-margin) + -11px);
            }

            .MbEPDb {
                margin-left: -4px;
                vertical-align: text-bottom
            }

            .hdtb-mitem .GOE98c,.hdtb-mitem a,.hdtb-mitem.hdtb-msel,.t2vtad {
                color: #969ba1;
                text-decoration: none;
                display: inline-block;
                padding: 0 12px;
                padding: 8px 16px 8px 16px;
                padding: 17px 12px 11px 10px
            }

            .hdtb-mitem {
                height: 16px;
                line-height: 16px;
                margin: 0 1px;
                display: inline-block
            }

            .hdtb-mitem a:active {
                color: #8ab4f8
            }

            .hdtb-mitem.hdtb-msel {
                color: #8ab4f8;
            }

            .cCvmNd .hdtb-mitem.hdtb-msel {
                border-bottom: none
            }

            .hdtb-mitem.hdtb-msel:hover {
                cursor: pointer
            }

            .hdtb-mitem.hdtb-msel:active {
                background: none
            }

            .hdtb-mitem a {
                color: #969ba1
            }

            .t2vtad {
                border: 1px solid transparent;
                text-align: center;
                border-radius: 2px;
                line-height: 19px;
                cursor: pointer;
                margin-left: -1px;
                padding: 4px 11px;
                margin-right: -11px;
            }

            .t2vtad:not(.hdtb-tl-sel):hover {
                box-shadow: 0 1px 1px rgba(23,23,23,0.9);
                -webkit-transition: all 0.0s;
                background-color: #303134;
                border: 1px solid #5f6368;
                color: #e8eaed
            }

            .t2vtad:active,.t2vtad:not(.hdtb-tl-sel):hover:active {
                background-color: #303134;
                box-shadow: inset 0 1px 2px rgba(23,23,23,0.9)
            }

            .YTDezd {
                background: #8ab4f8;
                height: 3px;
                margin-top: 11px
            }

            .bmaJhd {
                margin-right: 5px;
                vertical-align: text-bottom
            }

            .v7W49e {
                margin-top: 6px
            }

            [dir='ltr'],[dir='rtl'] {
                unicode-bidi: -webkit-isolate;
                unicode-bidi: isolate
            }

            bdo[dir='ltr'],bdo[dir='rtl'] {
                unicode-bidi: bidi-override;
                unicode-bidi: -webkit-isolate-override;
                unicode-bidi: isolate-override
            }

            .GyAeWb {
                display: flex;
                justify-content: flex-start;
                flex-wrap: wrap;
                max-width: calc(var(--center-abs-margin) + var(--center-width) + var(--rhs-margin) + var(--rhs-width) + var(--lhs-refinements-width));
            }

            .srp {
                --center-abs-margin: 180px;
                --center-width: 652px;
                --rhs-margin: 76px;
                --rhs-width: 372px;
                --lhs-refinements-width: 0px;
                position: relative;
                min-height: 100vh
            }

            @media (min-width: 1475px) and (max-width:1675px) {
                .srp {
                    --center-abs-margin:calc(25vw + -188.75px)
                }
            }

            @media (min-width: 1675px) {
                .srp {
                    --center-abs-margin:230px
                }
            }

            @media (min-width: 1124px) and (max-width:1300px) {
                .srp {
                    --center-abs-margin:calc((100vw - 1068px)/2)
                }
            }

            @media (max-width: 1124px) {
                .srp {
                    --center-abs-margin:28px
                }
            }

            .eqAnXb {
                font-size: medium;
                font-weight: normal;
            }

            .main {
                min-width: calc(var(--center-abs-margin) + var(--center-width) + var(--rhs-margin) + var(--rhs-width) + var(--lhs-refinements-width));
                width: 100%;
            }

            .s6JM6d {
                position: relative;
                width: var(--center-width);
                flex: 0 auto;
                margin-left: var(--center-abs-margin);
            }

            .e9EfHf {
                font-family: arial,sans-serif;
                clear: both;
                margin-left: 0;
                padding-top: 20px;
            }

            .dodTBe {
                height: 65px
            }

            .appbar {
                background: #202124;
                position: relative;
                -webkit-box-sizing: border-box;
                margin-left: var(--center-abs-margin);
            }
        </style>
    </head>
    <body jsmodel="hspDDf " class="srp" jscontroller="Eox39d" data-dt="1" marginheight="3" topmargin="3" jsaction="rcuQ6b:npT2md" id="gsr">
        <style>
            .wYq63b {
                display: flex;
                left: 0;
                position: absolute;
                top: 0;
                z-index: 1001
            }

            .S6VXfe {
                align-items: center;
                background-color: #202124;
                border-radius: 0 2px 2px 0;
                box-shadow: 0 2px 2px 0 rgba(0,0,0,.16),0 0 0 1px rgba(0,0,0,.08);
                display: flex;
                margin: 80px auto 8px 0;
                overflow: hidden
            }

            .gyPpGe,.gyPpGe:visited,.qlVNAd {
                border: 2px solid rgba(255,255,255,.16);
                border-radius: 2px;
                color: #c58af9;
                cursor: pointer;
                display: inline-block;
                font-size: 14px;
                line-height: 20px;
                margin: 6px 11px;
                min-height: 32px;
                text-decoration: underline;
                text-align: center;
                width: 106px
            }

            .gyPpGe:not(:focus) {
                clip: rect(1px,1px,1px,1px);
                overflow: hidden;
                position: absolute;
                padding: 0
            }

            .kur4we {
                display: none
            }

            a.oBa0Fe {
                color: #9aa0a6;
                float: right;
                font-style: italic;
                -webkit-tap-highlight-color: rgba(255,255,255,0);
                tap-highlight-color: rgba(255,255,255,0)
            }

            a.aciXEb {
                padding: 0 5px;
            }

            .CvDJxb {
                min-width: 1124px;
                width: 100%;
                z-index: 128;
                position: absolute;
                top: 20px;
                margin-top: 6px;
            }

            .tsf {
                width: calc(var(--center-abs-margin) + 652px);
            }

            .Q3DXx {
                display: flex
            }

            .Q3DXx.yIbDgf {
                justify-content: space-between
            }

            .Q3DXx #gb,.Q3DXx #gb>div {
                float: none
            }

            .CvDJxb iframe {
                color-scheme: light
            }

            .sfbg {
                background: #202124;
                height: 69px;
                left: 0;
                position: absolute;
                width: 100%
            }

            .minidiv .sfbg {
                height: 72px;
                overflow: hidden;
                background: #303134;
                box-shadow: 0 1px 6px 0 rgba(0,0,0,0.2)
            }

            .A8SBwf,.IormK {
                width: 692px;
                padding-left: 27px
            }

            .A8SBwf {
                margin: 0 auto;
                margin-left: calc(var(--center-abs-margin) - 47px);
                position: relative;
            }

            .RNNXgb {
                display: flex;
                z-index: 3;
                position: relative;
                min-height: 44px;
                background: #303134;
                border: 1px solid transparent;
                box-shadow: 0 1px 3px rgba(23,23,23,0.24);
                border-radius: 24px;
                margin: 0 auto;
                width: 690px;
            }

            .emcav .RNNXgb {
                border-bottom-left-radius: 0;
                border-bottom-right-radius: 0;
                box-shadow: 0 4px 12px rgba(23,23,23,0.9);
                background: #303134;
                border-color: rgba(223,225,229,0)
            }

            .minidiv .emcav .RNNXgb {
                border-color: transparent;
                border-bottom-left-radius: 0;
                border-bottom-right-radius: 0;
                box-shadow: 0 4px 12px rgba(23,23,23,0.9);
                border-color: rgba(223,225,229,0);
            }

            .RNNXgb:hover,.sbfc .RNNXgb {
                background-color: #303134;
                box-shadow: 0 4px 12px rgba(23,23,23,0.9);
                border-color: rgba(223,225,229,0)
            }

            .minidiv .RNNXgb:hover,.minidiv .sbfc .RNNXgb {
                border-color: rgba(223,225,229,0);
                box-shadow: 0 4px 12px rgba(23,23,23,0.9)
            }

            .minidiv .RNNXgb:hover {
                border-color: transparent;
                box-shadow: 0 4px 12px rgba(23,23,23,0.9)
            }

            .SDkEP {
                flex: 1;
                display: flex;
                padding: 5px 4px 0 14px;
            }

            .logo {
                position: absolute;
                left: -139px;
                padding: 4px 28px 0 30px;
                top: 6px;
            }

            .iblpc span {
                display: none
            }

            .sbfc .iblpc span,.emcav .iblpc span {
                display: block
            }

            .iblpc {
                display: flex;
                align-items: center;
                padding-right: 6px;
                margin-top: -7px
            }

            .sbfc .iblpc,.emcav .iblpc {
                padding-right: 14px;
                margin-left: -1px
            }

            .sbfc.A8SBwf,.emcav.A8SBwf {
                padding-left: 0;
                width: 719px
            }

            .sbfc .RNNXgb,.emcav .RNNXgb {
                width: 717px
            }

            @media (min-width: 0) {
                .emcav.A8SBwf.h3L8Ub {
                    width:calc(var(--center-width) + var(--rhs-margin) + var(--rhs-width) + 47px)
                }

                .emcav.h3L8Ub .RNNXgb {
                    width: calc(var(--center-width) + var(--rhs-margin) + var(--rhs-width) + 45px)
                }
            }

            @media (max-width: 1300px) {
                .emcav.A8SBwf.h3L8Ub {
                    width:calc(var(--rhs-margin) + var(--rhs-width) + var(--center-width) + -105px)
                }

                .emcav.h3L8Ub .RNNXgb {
                    width: calc(var(--rhs-margin) + var(--rhs-width) + var(--center-width) + -107px)
                }
            }

            .iblpc {
                display: flex;
                align-items: center;
                padding-right: 6px;
                margin-top: -7px;
                height: 46px
            }

            .M8H8pb {
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                padding: inherit;
                width: inherit
            }

            @media (max-width: 1300px) {
                .A8SBwf {
                    margin-left:calc(var(--center-abs-margin) + 105px)
                }
            }

            @media (max-width: 1300px) {
                .A8SBwf,.IormK {
                    width:540px
                }

                .RNNXgb {
                    width: 538px
                }

                .sbfc.A8SBwf,.emcav.A8SBwf {
                    width: 567px
                }

                .sbfc .RNNXgb,.emcav .RNNXgb {
                    width: 565px
                }
            }

            #logo {
                overflow: hidden;
                position: relative;
                display: block;
            }

            .jfN4p {
                border: 0
            }

            .CcAdNb {
                margin: auto
            }

            .QCzoEc {
                color: #9aa0a6
            }

            .DPXIy {
                display: flex;
                flex: 1
            }

            .gLFyf,.YacQv {
                font: 16px arial,sans-serif;
                line-height: 34px;
                font-size: 16px;
                flex: 100%;
                line-height: 39px
            }

            textarea.gLFyf,.YacQv {
                font-family: arial,sans-serif;
                font: 16px arial,sans-serif;
                line-height: 22px;
                margin-bottom: 8px;
                overflow-x: hidden
            }

            textarea.gLFyf {
                white-space: nowrap;
                overflow: hidden
            }

            .minidiv .gLFyf,.minidiv .YacQv {
                font-size: 14px;
                line-height: 22px;
                min-height: 22px !important;
            }

            .gLFyf {
                resize: none;
                background-color: transparent;
                border: none;
                margin: 0;
                padding: 0 0 3px;
                color: #e8eaed;
                word-wrap: break-word;
                outline: none;
                display: flex;
                -webkit-tap-highlight-color: transparent
            }

            .a4bIc {
                display: flex;
                flex-wrap: wrap;
                flex: 1;
                margin-top: 6px
            }

            .YacQv {
                color: transparent;
                white-space: pre;
                position: absolute;
                pointer-events: none
            }

            .YacQv span {
                text-decoration: #f28b82 dotted underline
            }

            .gLFyf.i4ySpb {
                display: block;
                position: absolute
            }

            .Sxjlmb {
                white-space: nowrap;
                margin: 20px;
                font-size: 14px;
                font-weight: bold;
                line-height: normal;
                color: #fff
            }

            .qfY0Jf {
                font-weight: normal;
                border: 1px solid #fff;
                border-radius: 3px;
                padding: 1px 3px 0 3px
            }

            .dRYYxd {
                display: flex;
                flex: 0 0 auto;
                margin-top: -5px;
                align-items: stretch;
                flex-direction: row;
                height: 44px
            }

            .BKRPef {
                background: transparent;
                align-items: center;
                flex: 1 0 auto;
                flex-direction: row;
                display: flex;
                cursor: pointer
            }

            .vOY7J {
                background: transparent;
                border: 0;
                align-items: center;
                flex: 1 0 auto;
                cursor: pointer;
                display: none;
                height: 100%;
                line-height: 44px;
                outline: none;
                padding: 0 12px
            }

            .M2vV3 {
                display: flex
            }

            .ExCKkf {
                height: 100%;
                color: #9aa0a6;
                vertical-align: middle;
                outline: none
            }

            .BKRPef {
                padding-right: 4px
            }

            .ACRAdd {
                border-left: 1px solid #5f6368;
                height: 65%
            }

            .ACRAdd {
                display: none
            }

            .ACRAdd.M2vV3 {
                display: block
            }

            .Umvnrc {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .ly0Ckb {
                background: url('//www.gstatic.com/inputtools/images/tia.png') no-repeat center;
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .yAnw3c {
                visibility: hidden
            }

            .XDyW0e {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .goxjub {
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .nDcEnd {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .Gdd5U {
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .Tg7LZd {
                height: 44px;
                width: 44px;
                background: transparent;
                border: none;
                cursor: pointer;
                flex: 0 0 auto;
                padding: 0;
            }

            .Tg7LZd {
                flex: 0 0 auto;
                padding-right: 13px
            }

            html:not(.zAoYTe) .Tg7LZd:focus {
                outline: none
            }

            .zgAlFc {
                background: none;
                color: #8ab4f8;
                height: 24px;
                width: 24px;
                margin: auto
            }

            .UUbT9 {
                position: absolute;
                text-align: left;
                z-index: 989;
                cursor: default;
                -webkit-user-select: none;
                width: 100%;
                margin-top: -1px;
            }

            .aajZCb {
                display: flex;
                flex-direction: column;
                margin: 0;
                padding: 0;
                overflow: hidden;
                background: #303134;
                border-radius: 0 0 24px 24px;
                box-shadow: 0 4px 6px 0 #171717;
                border: 0;
                padding-bottom: 4px;
            }

            .mkHrUc {
                display: flex;
            }

            .erkvQe {
                padding-bottom: 16px;
                flex: auto;
                overflow-x: hidden
            }

            .RjPuVb {
                height: 1px;
                margin: 0 26px 0 0;
            }

            .S3nFnd .RjPuVb,.S3nFnd .aajZCb {
                flex: 0 0 auto
            }

            .xtSCL {
                border-top: 1px solid #5f6368;
                margin: 0 14px;
                padding-bottom: 4px
            }

            #shJ2Vb {
                display: none
            }

            .OBMEnb {
                padding: 0;
                margin: 0
            }

            .OBMEnb:not(:first-child) {
                padding-top: 8px
            }

            .G43f7e {
                display: flex;
                flex-direction: column;
                min-width: 0;
                padding: 0;
                margin: 0;
                list-style: none
            }

            #ynRric {
                display: none
            }

            .ynRric {
                list-style-type: none;
                flex-direction: column;
                color: #9aa0a6;
                font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                font-size: 14px;
                margin: 0 20px 0 16px;
                padding: 8px 0 8px 0;
                line-height: 16px;
                width: 100%
            }

            .ynRric {
                letter-spacing: 0;
                text-transform: none
            }

            .sbct {
                display: flex;
                flex-direction: column;
                min-width: 0;
                overflow: hidden;
                max-height: none;
                padding: 0;
            }

            .eIPGRd {
                flex: auto;
                display: flex;
                align-items: center;
                margin: 0 20px 0 14px
            }

            .pcTkSc {
                display: flex;
                flex: auto;
                flex-direction: column;
                min-width: 0;
                max-height: none;
                padding: 6px 0
            }

            .sbic {
                display: flex;
                align-items: center;
                margin-right: 14px;
            }

            .ClJ9Yb {
                line-height: 12px;
                font-size: 13px;
                color: #9aa0a6;
                margin-top: 2px;
                padding-right: 8px
            }

            .wM6W7d {
                display: flex;
                font-size: 16px;
                color: #e8eaed;
                flex: auto;
                align-items: center;
                word-break: break-word;
                padding-right: 8px
            }

            .wM6W7d span {
                flex: auto
            }

            .AQZ9Vd {
                display: flex;
                align-self: stretch;
            }

            .UUbT9.i1eWpb .PZPZlf.sbhl .gmlSVb {
                background: rgba(255,119,105,.12)
            }

            .TfeWfb {
                display: none
            }

            .xAmryf {
                display: none
            }

            .DJbVFb .a5RLac {
                line-height: 24px;
                font-size: 20px;
                font-family: arial,sans-serif;
                padding-top: 16px;
                color: #bdc1c6;
                margin-bottom: auto
            }

            .DJbVFb .wM6W7d span {
                color: #e8eaed;
                line-height: 36px;
                font-weight: 400;
                font-size: 28px;
                font-family: Google Sans,arial,sans-serif
            }

            .iQxPRb {
                display: flex;
                gap: 2px
            }

            #bgeLZd {
                display: none
            }

            .xAmryf {
                box-sizing: border-box;
                align-items: center;
                height: 40px;
                border-radius: 8px;
                display: flex;
                color: #bdc1c6;
                border: 1px solid #3c4043;
                background-color: #202124;
                line-height: 22px
            }

            .jtAOgd {
                white-space: nowrap;
                font-family: Google Sans,arial,sans-serif;
                font-size: 14px;
                margin: 0 14px
            }

            .TfeWfb {
                gap: 12px 6px;
                overflow-x: auto;
                -ms-overflow-style: none;
                scrollbar-width: none
            }

            .TfeWfb::-webkit-scrollbar {
                display: none
            }

            #YMXe {
                display: none
            }

            .MagqMc .ZFiwCf {
                background-color: #303134;
                border: 1px solid #3c4043;
                width: 100%
            }

            .MagqMc.U48fD {
                padding: 0;
                margin-top: 16px
            }

            .MagqMc .Bi9oQd {
                display: none
            }

            .MagqMc {
                padding: 0
            }

            .MagqMc:hover .LGwnxb {
                color: #e8eaed
            }

            .U48fD {
                -webkit-tap-highlight-color: transparent;
                cursor: pointer;
                display: block;
                line-height: 18px;
                text-overflow: ellipsis;
                white-space: nowrap;
                padding: 16px;
                padding-top: 0;
                margin-top: 24px;
                position: relative
            }

            .ZFiwCf {
                display: flex;
                align-items: center;
                justify-content: center;
                position: relative;
                margin: 0 auto;
                font-size: 14px;
                font-family: arial,sans-serif;
                font-weight: 400;
                width: 100%;
                max-width: 300px;
                height: 36px;
                border-radius: 18px;
                background-color: #303134
            }

            @media (forced-colors:active) {
                .ZFiwCf {
                    border: 1px solid transparent
                }
            }

            .ZFiwCf:hover {
                background-color: #3c4043
            }

            .Bi9oQd {
                background-color: #3c4043;
                margin-top: 18px;
                position: absolute;
                border: 0;
                height: 1px;
                left: 0;
                width: 100%
            }

            .w2fKdd svg {
                width: auto
            }

            .w2fKdd {
                color: #9aa0a6
            }

            .LGwnxb {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
                width: auto;
                padding-left: 0;
                padding-right: 8px;
                max-width: 200px;
                color: #e8eaed
            }

            .LGwnxb:empty {
                padding-right: 0
            }

            .LGwnxb span,.LGwnxb div {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
                width: auto
            }

            @media (hover: hover) {
                .sbai {
                    visibility:hidden
                }

                .sbhl .sbai {
                    visibility: inherit
                }
            }

            #d6ItKb {
                display: none
            }

            .AB2Fdd {
                display: flex
            }

            .ZDHp {
                position: relative;
                margin: 20px;
                display: flex
            }

            .ZDHp .SHFPkb {
                margin-bottom: 12px
            }

            .o6OF0 .SHFPkb {
                line-height: 48px;
                font-family: Google Sans,arial,sans-serif;
                font-weight: 400;
                color: #e8eaed;
                display: -webkit-box;
                overflow: hidden;
                -webkit-line-clamp: 2;
                -webkit-box-orient: vertical
            }

            .o6OF0 .HrUlUc,.o6OF0 .PnfqLc {
                font-family: arial,sans-serif;
                font-weight: 400;
                max-height: 72px;
                color: #bdc1c6
            }

            .ZDHp .HrUlUc,.ZDHp .PnfqLc {
                font-size: 18px;
                line-height: 24px
            }

            .o6OF0 .bTSf5c {
                font-family: arial,sans-serif;
                font-weight: 400;
                color: #bdc1c6
            }

            .ZDHp .bTSf5c {
                line-height: 22px;
                font-size: 14px;
                margin-bottom: 6px
            }

            .ZDHp .HrUlUc,.ZDHp .PnfqLc {
                overflow: hidden;
                display: -webkit-box;
                -webkit-line-clamp: 3;
                -webkit-box-orient: vertical
            }

            .Vlt3wb {
                font-style: normal;
                font-family: arial,sans-serif;
                font-weight: 400;
                font-size: 14px;
                line-height: 22px;
                padding-top: 8px;
                margin-top: 12px;
                color: #bdc1c6;
                border-top: 1px solid #5f6368;
                display: flex;
                width: 100%
            }

            .Tnv2td {
                position: absolute;
                top: 0;
                right: 0
            }

            .z76Rnb {
                padding: 6px;
                width: 24px;
                height: 24px;
                background-color: #303134;
                color: #9aa0a6;
                border-radius: 9999px;
                border: 1px solid #3c4043;
                cursor: pointer
            }

            .kZtr1b {
                display: flex;
                flex-direction: column;
                flex-grow: 1;
                min-width: 0
            }

            .XAFD5c {
                width: 200px;
                height: 200px;
                background-color: #303134;
                border-radius: 20px;
                margin-left: 20px;
                flex-shrink: 0;
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain
            }

            .o6OF0 .xAmryf {
                font-family: Google Sans,arial,sans-serif;
                margin: 0;
                height: 38px;
                background-color: #303134;
                border-radius: 100px;
                border: 1px solid #3c4043;
                color: #bdc1c6;
                align-items: center;
                text-align: center;
                flex: none;
                cursor: pointer
            }

            .ZDHp .lnnVSe {
                font-size: 18px;
                flex-grow: 1
            }

            .ZDHp .HrUlUc,.ZDHp .PnfqLc {
                display: flex;
                flex-direction: column
            }

            .AsqS6c {
                display: block;
                margin: 20px
            }

            .gfT7kc {
                display: flex;
                flex-grow: 1;
                max-width: 100%
            }

            .cJpYle {
                display: flex;
                padding-right: 20px;
                flex-grow: 1;
                max-width: 50%;
                box-sizing: border-box
            }

            .gTtFDd {
                display: flex;
                padding-left: 20px;
                border-left: 1px solid #3c4043;
                flex-grow: 1;
                max-width: 50%;
                box-sizing: border-box
            }

            .AsqS6c .SHFPkb,.AsqS6c .bTSf5c,.AsqS6c .PnfqLc {
                padding-right: 0;
                margin-bottom: 10px
            }

            .AsqS6c .bTSf5c,.AsqS6c .PnfqLc {
                -webkit-line-clamp: 2;
                line-height: 24px;
                font-size: 18px;
                overflow: hidden;
                display: -webkit-box;
                -webkit-box-orient: vertical
            }

            .AsqS6c .HrUlUc {
                line-height: 22px;
                font-size: 14px;
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap
            }

            .AsqS6c .XAFD5c {
                width: 100px;
                height: 100px;
                background-color: #303134;
                border-radius: 16px;
                background-position: center;
                background-repeat: no-repeat
            }

            #JglY8e {
                display: none
            }

            .W3CMNd {
                display: flex
            }

            #mitGyb {
                display: none
            }

            #TN4rFf {
                display: none
            }

            .IDVnvc {
                display: inline-block;
                overflow: hidden;
                max-width: 223px;
                border-radius: 16px;
                height: 178px;
                margin: -2px -10px 2px 10px
            }

            .OBMEnb:only-child .IDVnvc {
                margin-right: calc(25% - 113px)
            }

            .cRV9hb {
                width: 90px;
                padding: 6px
            }

            .cRV9hb .pcTkSc {
                font-family: arial,sans-serif;
                overflow: hidden;
                margin-top: 4px;
                padding: 0
            }

            .cRV9hb .pcTkSc .wM6W7d {
                font-size: 14px;
                line-height: 18px;
                padding: 0;
                color: #bdc1c6
            }

            .cRV9hb .pcTkSc .ClJ9Yb {
                line-height: 16px;
                font-size: 12px;
                display: none;
                display: flex
            }

            .cRV9hb .pcTkSc .wM6W7d span,.cRV9hb .pcTkSc .ClJ9Yb span {
                overflow: hidden;
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                white-space: normal
            }

            .cRV9hb .pcTkSc .wM6W7d span {
                -webkit-line-clamp: 2
            }

            .cRV9hb .pcTkSc .ClJ9Yb span {
                -webkit-line-clamp: 2
            }

            .aVbWac {
                background: #fff;
                border-radius: 12px;
                height: 90px
            }

            @media (max-width: 1300px) {
                .A8SBwf:not(.h3L8Ub) .IDVnvc {
                    height:167px
                }

                .A8SBwf:not(.h3L8Ub) .cRV9hb {
                    width: 79px
                }

                .A8SBwf:not(.h3L8Ub) .aVbWac {
                    height: 79px
                }

                .A8SBwf:not(.h3L8Ub) .aVbWac .sbic.vYOkbe {
                    height: 79px;
                    width: 79px
                }
            }

            .MG7lrf {
                font-size: 8pt;
                margin-top: -16px;
                position: absolute;
                right: 16px;
            }

            #TWnylf {
                display: none
            }

            .KxWPre {
                display: flex;
                justify-content: flex-start;
                padding-right: 12px;
                margin: 8px 0 4px
            }

            .E2ShOd {
                font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                line-height: 16px;
                color: #9aa0a6;
                font-weight: 500;
                font-size: 14px;
                text-align: center
            }

            .VUsake {
                flex: 1
            }

            .KxWPre {
                padding-right: 18px;
                padding-left: 14px;
                align-items: center
            }

            .E2ShOd {
                margin: 0 20px 0 0
            }

            .V7WNjc {
            }

            .wSGdUc {
                width: 24px;
                height: 24px;
                color: #757575;
            }

            .Shjy3b {
                background: white
            }

            .GuoVP {
                color: #bdc1c6;
                font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                font-size: 16px
            }

            .Shjy3b {
                border-radius: 4px
            }

            .GuoVP {
                padding: 2px 20px
            }

            #dh215c {
                display: none
            }

            .zs1JGd {
                padding: 4px 0;
                display: flex;
                align-items: center;
                min-width: 0
            }

            .JqPLlb {
                font-size: 16px;
                color: #9aa0a6;
                flex: 1;
                align-items: center;
                word-break: break-word
            }

            .zs1JGd {
                cursor: pointer;
                margin-left: 14px
            }

            .JqPLlb {
                padding: 6px 0;
                color: #9aa0a6
            }

            .c58wS {
                display: flex;
                margin-right: -14px;
                position: relative;
                z-index: 99
            }
        </style>
        <div id="_WrGXZcTbGIHc1e8P9Y2o8A8_1"></div>
        <div jscontroller="nMfH9e" data-et="30" hidden="true" jsaction="rcuQ6b:npT2md"></div>
        <noscript>
            <style>
                table,div,span,p {
                    display: none
                }
            </style>
            <meta content="0;url=/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;gbv=1&amp;sei=WrGXZcTbGIHc1e8P9Y2o8A8" http-equiv="refresh">
            <div style="display:block">
                Xin vui lòng nhấn <a href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;gbv=1&amp;sei=WrGXZcTbGIHc1e8P9Y2o8A8">vào đây</a>
                nếu bạn không được chuyển đi trong vòng vài giây.
            </div>
        </noscript>
        <style>
            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Kwp5MKg.woff2)format('woff2');
                unicode-range: U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Nwp5MKg.woff2)format('woff2');
                unicode-range: U+0370-03FF;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Bwp5MKg.woff2)format('woff2');
                unicode-range: U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Awp5MKg.woff2)format('woff2');
                unicode-range: U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Owp4.woff2)format('woff2');
                unicode-range: U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;
            }
        </style>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                var w = ["Google Sans", [400]];
                (function() {
                    if (document.fonts && document.fonts.load)
                        for (var a = 0; a < w.length; a += 2)
                            for (var d = w[a], e = w[a + 1], b = 0, c = void 0; c = e[b]; ++b)
                                document.fonts.load(c + " 10pt " + d).catch(function() {})
                }
                )();
            }
            )();
        </script>
        <h2 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Liên kết hỗ trợ truy cập</h2>
        <div jscontroller="EufiNb" class="wYq63b">
            <div class="S6VXfe">
                <a jsname="BKxS1e" class="gyPpGe" role="link" tabindex="0" jsaction="i3viod" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q67oDCAU">Bỏ qua để đến phần nội dung chính</a>
                <a jsname="PwyVob" class="o8xTWc kur4we gyPpGe" href="#" role="link" jsaction="xoizsc">Tắt chế độ cuộn liên tục</a>
                <a jsname="BzS6B" class="wxIowe kur4we gyPpGe" href="#" role="link" jsaction="XZ94se">Bật chế độ cuộn liên tục</a>
                <span id="tsuid_3"></span>
                <a jsname="KI37ad" class="gyPpGe" href="https://support.google.com/websearch/answer/181196?hl=vi" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;url=https://support.google.com/websearch/answer/181196%3Fhl%3Dvi&amp;ved=0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QwcMDCAc&amp;bl=Qwmp&amp;opi=89978449">Hỗ trợ truy cập</a>
                <div data-async-context="async_id:duf3-78;authority:0;card_id:;entry_point:0;feature_id:;ftoe:0;header:0;is_jobs_spam_form:0;open:0;preselect_answer_index:-1;suggestions:;suggestions_subtypes:;suggestions_types:;surface:0;title:;type:78">
                    <div jscontroller="EkevXb" style="display:none" jsaction="rcuQ6b:npT2md"></div>
                    <div id="duf3-78" data-jiis="up" data-async-type="duffy3" data-async-context-required="type,open,feature_id,async_id,entry_point,authority,card_id,ftoe,title,header,suggestions,surface,suggestions_types,suggestions_subtypes,preselect_answer_index,is_jobs_spam_form" class="yp" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q-0EICA"></div>
                    <a jsname="JUypV" class="gyPpGe" data-async-trigger="duf3-78" role="link" tabindex="0" jsaction="trigger.szjOR">Phản hồi về hỗ trợ truy cập</a>
                </div>
            </div>
        </div>
        <div class="CvDJxb" jscontroller="tIj4fb" jsaction="rcuQ6b:npT2md;" id="searchform">
            <div style="margin-top:-20px" class="sfbg"></div>
            <div class="Q3DXx yIbDgf">
                <form class="tsf" action="/search" id="tsf" autocomplete="off" data-submitfalse="q" method="GET" name="f" role="search">
                    <div jsmodel="ZrDSAb vNzKHd" jsdata="MuIEvd;_;Bmu0rE">
                        <div jscontroller="cnjECf" jsmodel="VYkzu kjkykd a4L2gc LM7wx BFDhle gx0hCb TnHSdd L97mud " class="A8SBwf" data-adhe="false" data-alt="true" data-biboe="false" data-efaql="false" data-ehswwf="false" data-hp="false" data-mof="false" jsdata="LVplcb;_;" jsaction="lX6RWd:w3Wsmc;ocDSvd:duwfG;DR74Fd:KyvVPe;DkpM0b:d3sQLd;IQOavd:dFyQEf;XzZZPe:jI3wzf;Aghsf:AVsnlb;iHd9U:Q7Cnrc;f5hEHe:G0jgYd;vmxUb:j3bJnb;nTzfpf:YPRawb;R2c5O:LuRugf;qiCkJd:ANdidc;htNNz:SNIJTd;NOg9L:HLgh3;uGoIkd:epUokb;zLdLw:eaGBS;H9muVd:J4e6lb;djyPCf:nMeUJf;hBEIVb:nUZ9le;rcuQ6b:npT2md">
                            <div class="logo">
                                <a href="https://www.google.com/webhp?hl=vi&amp;sa=X&amp;ved=0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QPAgJ" title="Đến trang chủ Google" id="logo" data-hveid="9">
                                    <img class="jfN4p" src="/images/branding/googlelogo/2x/googlelogo_light_color_92x30dp.png" style="background:none" alt="Google" height="30" width="92">
                                </a>
                            </div>
                            <div class="RNNXgb" jsname="RNNXgb">
                                <div class="SDkEP">
                                    <div class="iblpc" jsname="uFMOof">
                                        <div class="CcAdNb">
                                            <span class="QCzoEc z1asCe MZy1Rb" style="height:20px;line-height:20px;width:20px">
                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                    <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                                                </svg>
                                            </span>
                                        </div>
                                    </div>
                                    <div jscontroller="vZr2rb" class="a4bIc" data-hpmde="false" data-mnr="4" jsname="gLFyf" jsaction="h5M12e;input:d3sQLd;blur:jI3wzf;keydown:uYT2Vb">
                                        <div class="DPXIy">
                                            <div jsname="vdLsw" class="YacQv"></div>
                                            <div jsname="aJyGR" jscontroller="xMclgd" class="gLFyf i4ySpb" data-promo-open-duration="2000" jsaction="rcuQ6b:npT2md">
                                                <g-snackbar jsname="nH91he" jscontroller="OZLguc" style="display:none" data-dismiss="" jsshadow="" jsaction="rcuQ6b:npT2md">
                                                    <div jsname="sM5MNb" aria-live="polite" class="jhZvod">
                                                        <div jsname="Ng57nc" class="Wu0v9b v0rrvd" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4G8ICw">
                                                            <div class="b77HKf">
                                                                <div class="rIxsve" jsslot="">
                                                                    <span class="Txngnb wHYlTd yUTMj Sxjlmb">
                                                                        Nhấn <span class="qfY0Jf">/</span>
                                                                        để chuyển tới hộp tìm kiếm
                                                                    </span>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </g-snackbar>
                                            </div>
                                            <textarea jsname="yZiJbe" class="gLFyf" jsaction="paste:puy29d; mouseenter:MJEKMe; mouseleave:iFHZnf;" id="APjFqb" maxlength="2048" name="q" rows="1" aria-activedescendant="" aria-autocomplete="both" aria-controls="Alh6id" aria-expanded="false" aria-haspopup="both" aria-owns="Alh6id" autocapitalize="off" autocomplete="off" autocorrect="off" role="combobox" spellcheck="false" type="search" value="code mẫu" aria-label="Tìm kiếm" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q39UDCAw">code mẫu</textarea>
                                        </div>
                                    </div>
                                    <div class="dRYYxd">
                                        <div jscontroller="PymCCe" jsname="RP0xob" class="BKRPef">
                                            <div class="M2vV3 vOY7J" tabindex="0" jsname="pkjasb" aria-label="Xóa" role="button" jsaction="AVsnlb;rcuQ6b:npT2md" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q05YFCA0">
                                                <span class="ExCKkf z1asCe rzyADb" jsname="itVqKe">
                                                    <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                        <path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path>
                                                    </svg>
                                                </span>
                                            </div>
                                            <span jsname="s1VaRe" class="ACRAdd M2vV3"></span>
                                        </div>
                                        <div jscontroller="Y9t9Sc" class="Umvnrc" aria-label="Công cụ nhập" role="button" tabindex="0" jsaction="h5M12e;rcuQ6b:npT2md">
                                            <span class="ly0Ckb">
                                                <img class="yAnw3c" src="/tia/tia.png" tia_disable_swap="true" tia_field_name="q" jsname="JyIpdf">
                                            </span>
                                        </div>
                                        <div jscontroller="unV4T" jsname="F7uqIe" class="XDyW0e" aria-label="Tìm kiếm bằng giọng nói" role="button" tabindex="0" jsaction="h5M12e;rcuQ6b:npT2md" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qvs8DCA4">
                                            <svg class="goxjub" focusable="false" viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                                <path fill="#4285f4" d="m12 15c1.66 0 3-1.31 3-2.97v-7.02c0-1.66-1.34-3.01-3-3.01s-3 1.34-3 3.01v7.02c0 1.66 1.34 2.97 3 2.97z"></path>
                                                <path fill="#34a853" d="m11 18.08h2v3.92h-2z"></path>
                                                <path fill="#fbbc04" d="m7.05 16.87c-1.27-1.33-2.05-2.83-2.05-4.87h2c0 1.45 0.56 2.42 1.47 3.38v0.32l-1.15 1.18z"></path>
                                                <path fill="#ea4335" d="m12 16.93a4.97 5.25 0 0 1 -3.54 -1.55l-1.41 1.49c1.26 1.34 3.02 2.13 4.95 2.13 3.87 0 6.99-2.92 6.99-7h-1.99c0 2.92-2.24 4.93-5 4.93z"></path>
                                            </svg>
                                        </div>
                                        <div jscontroller="lpsUAf" jsname="R5mgy" class="nDcEnd" data-base-lens-url="https://lens.google.com" data-image-processor-enabled="true" data-is-images-mode="false" data-preferred-mime-type="image/jpeg" data-propagated-experiment-ids="" aria-label="Tìm kiếm bằng hình ảnh" role="button" tabindex="0" jsaction="rcuQ6b:npT2md;h5M12e" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QhqEICA8">
                                            <svg class="Gdd5U" focusable="false" viewbox="0 0 192 192" xmlns="http://www.w3.org/2000/svg">
                                                <rect fill="none" height="192" width="192"></rect>
                                                <g>
                                                    <circle fill="#34a853" cx="144.07" cy="144" r="16"></circle>
                                                    <circle fill="#4285f4" cx="96.07" cy="104" r="24"></circle>
                                                    <path fill="#ea4335" d="M24,135.2c0,18.11,14.69,32.8,32.8,32.8H96v-16l-40.1-0.1c-8.8,0-15.9-8.19-15.9-17.9v-18H24V135.2z"></path>
                                                    <path fill="#fbbc04" d="M168,72.8c0-18.11-14.69-32.8-32.8-32.8H116l20,16c8.8,0,16,8.29,16,18v30h16V72.8z"></path>
                                                    <path fill="#4285f4" d="M112,24l-32,0L68,40H56.8C38.69,40,24,54.69,24,72.8V92h16V74c0-9.71,7.2-18,16-18h80L112,24z"></path>
                                                </g>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                                <button jsname="Tg7LZd" class="Tg7LZd" aria-label="Tìm kiếm" type="submit" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4dUDCBA">
                                    <div class="zgAlFc">
                                        <span class="z1asCe MZy1Rb">
                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                                            </svg>
                                        </span>
                                    </div>
                                </button>
                            </div>
                            <div jscontroller="Dvn7fe" class="UUbT9 EyBRub" style="display:none" jsname="UUbT9" jsaction="mouseout:ItzDCd;mouseleave:MWfikb;hBEIVb:nUZ9le;YMFC3:VKssTb;vklu5c:k02QY;ldyIye:CmVOgc" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4tUDCBE">
                                <div class="RjPuVb" jsname="RjPuVb"></div>
                                <div class="aajZCb" jsname="aajZCb">
                                    <div class="xtSCL"></div>
                                    <div class="mkHrUc" id="Alh6id" role="presentation">
                                        <div class="erkvQe" jsname="erkvQe"></div>
                                        <div class="rLrQHf" jsname="tovEib" role="presentation"></div>
                                    </div>
                                    <div jsname="E80e9e" class="OBMEnb" id="shJ2Vb" role="presentation">
                                        <ul jsname="bw4e9b" class="G43f7e" role="listbox"></ul>
                                    </div>
                                    <div jsname="XiTF2e" class="OBMEnb" role="presentation">
                                        <div jsname="Q7Erhd" class="G43f7e" role="presentation"></div>
                                    </div>
                                    <div class="ynRric" id="ynRric" role="presentation"></div>
                                    <li data-view-type="1" class="sbct" id="YMXe" role="presentation">
                                        <div class="eIPGRd">
                                            <div class="sbic">
                                                <div class="j0GJWd" style="display:none">
                                                    <div>
                                                        <img class="uHGFVd AZNDm" alt="" style="display:none">
                                                    </div>
                                                    <div class="iQxPRb">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="pcTkSc">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                    <div class="a5RLac">
                                                        <span></span>
                                                    </div>
                                                </div>
                                                <div class="Sz7Lee MagqMc U48fD" style="display:none" aria-label="Xem thêm" role="button" tabindex="0">
                                                    <hr class="Bi9oQd" aria-hidden="true">
                                                    <div class="ZFiwCf">
                                                        <span class="LGwnxb">Xem thêm</span>
                                                        <span class="w2fKdd z1asCe" style="height:20px;line-height:20px;width:20px">
                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                <path d="M12 4l-1.41 1.41L16.17 11H4v2h12.17l-5.58 5.59L12 20l8-8z"></path>
                                                            </svg>
                                                        </span>
                                                    </div>
                                                </div>
                                                <div class="TfeWfb"></div>
                                            </div>
                                            <div class="AQZ9Vd" aria-atomic="true" role="button">
                                                <div class="sbai" role="presentation">Xoá</div>
                                            </div>
                                        </div>
                                    </li>
                                    <div class="xAmryf" id="bgeLZd">
                                        <span class="jtAOgd"></span>
                                    </div>
                                    <li class="AB2Fdd" data-view-type="9" id="d6ItKb" role="presentation">
                                        <div class="eIPGRd">
                                            <div class="ZDHp" id="fU0xAb" role="presentation" style="display:none">
                                                <div class="kZtr1b">
                                                    <div class="lnnVSe" aria-atomic="true" role="option">
                                                        <div class="SHFPkb"></div>
                                                        <div class="bTSf5c"></div>
                                                        <div class="PnfqLc"></div>
                                                        <div class="HrUlUc"></div>
                                                    </div>
                                                    <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                        <span class="z76Rnb z1asCe JKu1je">
                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                            </svg>
                                                        </span>
                                                    </div>
                                                    <div class="xAmryf" id="bgeLZd">
                                                        <span class="jtAOgd"></span>
                                                    </div>
                                                    <div class="TfeWfb" role="presentation" style="display:none"></div>
                                                    <div class="Vlt3wb" style="display:none"></div>
                                                </div>
                                                <span class="XAFD5c" style="display:none"></span>
                                                <div class="j0GJWd" style="display:none">
                                                    <div>
                                                        <img class="uHGFVd AZNDm" alt="" style="display:none">
                                                    </div>
                                                    <div class="iQxPRb">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </li>
                                    <li class="W3CMNd" data-view-type="10" id="JglY8e" role="option">
                                        <div class="eIPGRd" role="presentation">
                                            <div class="AsqS6c" id="GTYqfc" role="presentation" style="display:none">
                                                <div class="gfT7kc">
                                                    <div class="cJpYle">
                                                        <div class="lnnVSe" aria-atomic="true" role="option">
                                                            <div class="SHFPkb"></div>
                                                            <div class="bTSf5c"></div>
                                                            <div class="PnfqLc"></div>
                                                            <div class="HrUlUc"></div>
                                                        </div>
                                                        <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                            <span class="z76Rnb z1asCe JKu1je">
                                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                    <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                                </svg>
                                                            </span>
                                                        </div>
                                                        <span class="XAFD5c" style="display:none"></span>
                                                    </div>
                                                    <div class="gTtFDd">
                                                        <div class="lnnVSe" aria-atomic="true" role="option">
                                                            <div class="SHFPkb"></div>
                                                            <div class="bTSf5c"></div>
                                                            <div class="PnfqLc"></div>
                                                            <div class="HrUlUc"></div>
                                                        </div>
                                                        <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                            <span class="z76Rnb z1asCe JKu1je">
                                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                    <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                                </svg>
                                                            </span>
                                                        </div>
                                                        <span class="XAFD5c" style="display:none"></span>
                                                    </div>
                                                </div>
                                                <div class="xAmryf" id="bgeLZd">
                                                    <span class="jtAOgd"></span>
                                                </div>
                                                <div class="TfeWfb" role="presentation" style="display:none"></div>
                                                <div class="Vlt3wb" style="display:none"></div>
                                            </div>
                                        </div>
                                    </li>
                                    <li data-view-type="8" class="sbct" id="mitGyb" role="presentation">
                                        <div class="eIPGRd hdt0ld">
                                            <div class="sbic"></div>
                                            <div class="pcTkSc">
                                                <div>
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="AQZ9Vd" aria-atomic="true" role="button">
                                                <div class="sbai" role="presentation">Xoá</div>
                                            </div>
                                        </div>
                                    </li>
                                    <div class="ZDHp" id="fU0xAb" role="presentation" style="display:none">
                                        <div class="kZtr1b">
                                            <div class="lnnVSe" aria-atomic="true" role="option">
                                                <div class="SHFPkb"></div>
                                                <div class="bTSf5c"></div>
                                                <div class="PnfqLc"></div>
                                                <div class="HrUlUc"></div>
                                            </div>
                                            <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                <span class="z76Rnb z1asCe JKu1je">
                                                    <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                        <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                    </svg>
                                                </span>
                                            </div>
                                            <div class="xAmryf" id="bgeLZd">
                                                <span class="jtAOgd"></span>
                                            </div>
                                            <div class="TfeWfb" role="presentation" style="display:none"></div>
                                            <div class="Vlt3wb" style="display:none"></div>
                                        </div>
                                        <span class="XAFD5c" style="display:none"></span>
                                        <div class="j0GJWd" style="display:none">
                                            <div>
                                                <img class="uHGFVd AZNDm" alt="" style="display:none">
                                            </div>
                                            <div class="iQxPRb">
                                                <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                            </div>
                                        </div>
                                    </div>
                                    <div class="AsqS6c" id="GTYqfc" role="presentation" style="display:none">
                                        <div class="gfT7kc">
                                            <div class="cJpYle">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="SHFPkb"></div>
                                                    <div class="bTSf5c"></div>
                                                    <div class="PnfqLc"></div>
                                                    <div class="HrUlUc"></div>
                                                </div>
                                                <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                    <span class="z76Rnb z1asCe JKu1je">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                        </svg>
                                                    </span>
                                                </div>
                                                <span class="XAFD5c" style="display:none"></span>
                                            </div>
                                            <div class="gTtFDd">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="SHFPkb"></div>
                                                    <div class="bTSf5c"></div>
                                                    <div class="PnfqLc"></div>
                                                    <div class="HrUlUc"></div>
                                                </div>
                                                <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                    <span class="z76Rnb z1asCe JKu1je">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                        </svg>
                                                    </span>
                                                </div>
                                                <span class="XAFD5c" style="display:none"></span>
                                            </div>
                                        </div>
                                        <div class="xAmryf" id="bgeLZd">
                                            <span class="jtAOgd"></span>
                                        </div>
                                        <div class="TfeWfb" role="presentation" style="display:none"></div>
                                        <div class="Vlt3wb" style="display:none"></div>
                                    </div>
                                    <li class="IDVnvc" data-view-type="6" id="TN4rFf" role="presentation">
                                        <div class="cRV9hb">
                                            <div class="aVbWac">
                                                <div class="sbic"></div>
                                            </div>
                                            <div class="pcTkSc" role="presentation">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </li>
                                </div>
                                <div jscontroller="OqGDve" jsname="JUypV">
                                    <div class="MG7lrf" jsname="kAiEt" data-async-context="async_id:duf3-46;authority:0;card_id:;entry_point:0;feature_id:;ftoe:0;header:0;is_jobs_spam_form:0;open:0;preselect_answer_index:-1;suggestions:;suggestions_subtypes:;suggestions_types:;surface:0;title:;type:46">
                                        <div jscontroller="EkevXb" style="display:none" jsaction="rcuQ6b:npT2md"></div>
                                        <div id="duf3-46" data-jiis="up" data-async-type="duffy3" data-async-context-required="type,open,feature_id,async_id,entry_point,authority,card_id,ftoe,title,header,suggestions,surface,suggestions_types,suggestions_subtypes,preselect_answer_index,is_jobs_spam_form" class="yp" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q-0EIEw"></div>
                                        <a class="oBa0Fe aciXEb" href="#" id="sbfblt" data-async-trigger="duf3-46" aria-label="Gửi ý kiến phản hồi về kết quả này" role="button" jsaction="trigger.szjOR" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qtw8IFA">Báo cáo các gợi ý không phù hợp</a>
                                    </div>
                                </div>
                                <div class="KxWPre" id="TWnylf">
                                    <div class="E2ShOd"></div>
                                    <span class="VUsake"></span>
                                    <g-dropdown-menu class="V7WNjc" jscontroller="pFsdhd" jsdata="xJGXK;_;Bmu0rI" jsshadow="" jsaction="rcuQ6b:npT2md;mMf61e:GKlhgf;YraOve:cCpuJc;kNOP9c:bzkPEc;hmb6Ye:oyYkKb;KyPa0e:G8Ofmd;wjOG7e:rWoVB;ZvRO4b:L76sMb;LyWNEf:L76sMb">
                                        <g-popup jsname="zpo2ue" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;Bmu0rM">
                                            <div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" jsslot="" role="button" tabindex="0" aria-label="Xem thêm" jsaction="WFrRFb;keydown:uYT2Vb">
                                                <div class="wSGdUc">
                                                    <span class="IjabWd z1asCe SaPW2b">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                        </svg>
                                                    </span>
                                                </div>
                                            </div>
                                            <div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:1000">
                                                <g-menu jsname="iXXGtd" class="WNN1b Shjy3b yTik0 wplJBd PBn44e iQXTJe" jscontroller="WlNQGd" role="menu" tabindex="-1" jsaction="PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c">
                                                    <g-menu-item jsname="NNJLud" class="GuoVP EpPYLd GZnQqe" jscontroller="CnSW2d" role="menuitem" tabindex="-1" data-short-label="" jsdata="zPXzie;_;Bmu0rQ">
                                                        <div jsname="ibnC6b" class="YpcDnf OSrXXb">Bỏ qua</div>
                                                    </g-menu-item>
                                                </g-menu>
                                            </div>
                                        </g-popup>
                                    </g-dropdown-menu>
                                </div>
                                <div class="zs1JGd" data-view-type="7" jsname="RqJ7oe" id="dh215c" role="presentation">
                                    <div class="JqPLlb" role="option" tabindex="0"></div>
                                </div>
                            </div>
                            <div jsname="mvaK7d" class="M8H8pb" data-ved="0ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4d8ICBg"></div>
                        </div>
                        <div style="background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp)"></div>
                    </div>
                    <div id="tophf">
                        <input name="sca_esv" value="595895911" type="hidden">
                        <input name="sxsrf" value="AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411" type="hidden">
                        <input value="WrGXZcTbGIHc1e8P9Y2o8A8" name="ei" type="hidden">
                        <input value="AO6bgOgAAAAAZZe_arl06aRLJh7-_kKyFjYgcj2IwAOL" disabled="true" name="iflsig" type="hidden">
                    </div>
                </form>
                <div class="Q3DXx">
                    <div class="c58wS">
                        <div id="_WrGXZcTbGIHc1e8P9Y2o8A8_5" jscontroller="vTw9Fc" jsname="gRWMdb" data-triggering-tag="UMK4Dc" jsaction="fj1r1d:qiause"></div>
                    </div>
                    <div id="_WrGXZcTbGIHc1e8P9Y2o8A8_7"></div>
                </div>
            </div>
        </div>
        <div id="gac_scont"></div>
        <span class="kpshf line gsr bilit big mdm" style="display:none"></span>
        <div class="main" id="main">
            <div jsmodel=" ROaKxe" class="e9EfHf" id="cnt">
                <div class="dodTBe" id="sfcnt"></div>
                <style>
                    .YrbPuc {
                        color: #9aa0a6;
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        font-weight: 400;
                        line-height: 22px
                    }

                    .oPWl9c {
                        color: #9aa0a6;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 20px
                    }

                    .BjWz4c {
                        color: #9aa0a6;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 16px
                    }

                    .cj1ht {
                        color: #bdc1c6;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 16px
                    }

                    sentinel {
                    }

                    .SGNhVe {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 48px;
                        letter-spacing: 0;
                        line-height: 56px
                    }

                    .EX5Zne {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 36px;
                        line-height: 40px
                    }

                    .JgzqYd {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 28px;
                        line-height: 36px
                    }

                    .aTI8gc {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 28px;
                        font-weight: 400;
                        line-height: 36px
                    }

                    .IFnjPb {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 22px;
                        font-weight: 400;
                        line-height: 28px
                    }

                    .pb3iw {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 18px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .ILxcde {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 16px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .MBeuO {
                        font-family: arial,sans-serif;
                        font-size: 20px;
                        font-weight: 400
                    }

                    .MBeuO {
                        line-height: 24px
                    }

                    .tNxQIb {
                        font-family: arial,sans-serif;
                        font-size: 16px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .ZwRhJd {
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        line-height: 18px
                    }

                    .NNMgCf {
                        font-family: arial,sans-serif;
                        font-size: 18px;
                        line-height: 24px
                    }

                    .Pqkn2e {
                        font-family: arial,sans-serif;
                        font-size: 16px;
                        line-height: 24px
                    }

                    .wHYlTd {
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        line-height: 22px
                    }

                    .ApHyTb {
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        line-height: 16px
                    }

                    .sjVJQd {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 14px;
                        font-weight: 400;
                        line-height: 20px
                    }

                    .k1U36b {
                        font-size: 12px
                    }

                    sentinel {
                    }

                    .TGyDA {
                        height: 66px;
                        display: -css3-box;
                        -css3-box-orient: vertical;
                        -css3-line-clamp: 3;
                        overflow: hidden;
                        white-space: normal
                    }

                    .yUTMj {
                        font-family: arial,sans-serif;
                        font-weight: 400
                    }

                    .VDgVie {
                        text-align: center
                    }

                    .TUOsUe {
                        text-align: left
                    }

                    .AraNOb {
                        -webkit-text-decoration: underline;
                        text-decoration: underline
                    }

                    .BBwThe {
                        font-weight: 700
                    }

                    .RiJqbb {
                        font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                        font-weight: 500
                    }

                    .SlP8xc {
                        text-transform: none
                    }

                    .n9iHLc {
                        text-transform: uppercase
                    }

                    .OSrXXb {
                        overflow: hidden;
                        text-overflow: ellipsis
                    }

                    .cHaqb {
                        overflow: hidden;
                        text-overflow: ellipsis;
                        white-space: nowrap
                    }

                    .RES9jf {
                        color: #e8eaed
                    }

                    .GS5rRd {
                        color: #8ab4f8
                    }

                    .GS5rRd:visited {
                        color: #c58af9
                    }

                    .q8U8x {
                        font-family: Google Sans,arial,sans-serif;
                        font-weight: 400
                    }

                    sentinel {
                    }

                    .OhScic {
                        margin: 0px
                    }

                    .zsYMMe {
                        padding: 0px
                    }

                    .bNg8Rb {
                        clip: rect(1px,1px,1px,1px);
                        height: 1px;
                        overflow: hidden;
                        position: absolute;
                        white-space: nowrap;
                        width: 1px;
                        z-index: -1000;
                        user-select: none;
                        -webkit-user-select: none;
                        -moz-user-select: none;
                        -ms-user-select: none
                    }

                    sentinel {
                    }

                    .s6JM6d .eYa01b {
                        width: 148px
                    }

                    .s6JM6d .KtfA8c {
                        width: 204px
                    }

                    .s6JM6d .APo4S {
                        margin-left: 10px;
                        margin-right: 10px
                    }

                    .s6JM6d .THlyec {
                        margin-left: -10px;
                        margin-right: -10px;
                        width: auto
                    }

                    .M8OgIe .hhv4Fb {
                        margin-left: -38px;
                        margin-right: -38px
                    }

                    .M8OgIe .JL6v7b {
                        margin-left: 38px;
                        margin-right: 38px;
                        padding-left: 0;
                        padding-right: 0
                    }

                    .M8OgIe .TRty9d {
                        width: 316px
                    }

                    .TQc1id .zLsiYe {
                        margin-left: -21px;
                        padding-left: 0
                    }

                    sentinel {
                    }

                    .zJUuqf {
                        margin-bottom: 4px
                    }

                    .AB4Wff {
                        margin-left: 16px
                    }

                    .v0rrvd {
                        padding-bottom: 16px
                    }

                    @-webkit-keyframes g-snackbar-show {
                        from {
                            pointer-events: none;
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }

                        to {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }
                    }

                    @keyframes g-snackbar-show {
                        from {
                            pointer-events: none;
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }

                        to {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }
                    }

                    @-webkit-keyframes g-snackbar-hide {
                        from {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }

                        to {
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }
                    }

                    @keyframes g-snackbar-hide {
                        from {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }

                        to {
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }
                    }

                    @-webkit-keyframes g-snackbar-show-content {
                        from {
                            opacity: 0
                        }
                    }

                    @keyframes g-snackbar-show-content {
                        from {
                            opacity: 0
                        }
                    }

                    @-webkit-keyframes g-snackbar-hide-content {
                        to {
                            opacity: 0
                        }
                    }

                    @keyframes g-snackbar-hide-content {
                        to {
                            opacity: 0
                        }
                    }

                    .LH3wG,.jhZvod {
                        bottom: 0;
                        height: 0;
                        position: fixed;
                        z-index: 999
                    }

                    .Ox8Cyd {
                        height: 0;
                        position: fixed;
                        z-index: 999
                    }

                    .E7Hdgb {
                        box-sizing: border-box;
                        visibility: hidden;
                        display: inline-block
                    }

                    .yK6jqe,.Wu0v9b {
                        box-sizing: border-box;
                        visibility: hidden
                    }

                    .rTYTNb {
                        -webkit-animation: g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;
                        visibility: inherit
                    }

                    .UewPMd {
                        -webkit-animation: g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;
                        visibility: inherit
                    }

                    .b77HKf {
                        background-color: #3c4043;
                        padding: 0 24px
                    }

                    .rIxsve {
                        -webkit-box-align: center;
                        -webkit-align-items: center;
                        align-items: center;
                        box-align: center;
                        display: box;
                        display: -webkit-box;
                        display: -webkit-flex;
                        display: flex
                    }

                    .rTYTNb .rIxsve {
                        -webkit-animation: g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both
                    }

                    .UewPMd .rIxsve {
                        -webkit-animation: g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both;
                        animation: g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both
                    }

                    .Txngnb.Txngnb {
                        line-height: 20px
                    }

                    .Txngnb {
                        box-flex: 1;
                        color: #fff;
                        -webkit-box-flex: 1;
                        -webkit-flex: 1 1 auto;
                        flex: 1 1 auto;
                        margin: 14px 0;
                        word-break: break-word
                    }

                    .sHFNYd {
                        margin-right: -8px
                    }

                    @media (min-width: 569px) and (min-height:569px) {
                        .LH3wG,.jhZvod {
                            text-align:center
                        }

                        .Wu0v9b,.yK6jqe {
                            display: inline-block;
                            max-width: 568px;
                            min-width: 288px;
                            text-align: left
                        }

                        .b77HKf {
                            border-radius: 8px
                        }

                        .sHFNYd {
                            margin-left: 40px
                        }
                    }

                    .V9O1Yd .rIxsve {
                        display: block;
                        padding: 8px 0
                    }

                    .V9O1Yd .sHFNYd {
                        margin-left: 0
                    }

                    .V9O1Yd .sHFNYd g-flat-button {
                        padding-left: 0
                    }

                    .jhZvod {
                        left: 16px;
                        right: auto
                    }

                    .LH3wG,.Ox8Cyd {
                        left: 0;
                        right: 0
                    }

                    .yK6jqe,.Wu0v9b,.E7Hdgb {
                        position: relative
                    }

                    .G9jore {
                        position: absolute;
                        top: -24px;
                        bottom: -24px;
                        left: -24px;
                        right: -24px
                    }

                    sentinel {
                    }

                    .r2fjmd {
                        margin-bottom: 0px;
                        margin-top: 0px
                    }

                    g-dropdown-menu {
                        display: inline-block;
                        position: relative
                    }

                    .Jb0Zif g-dropdown-menu {
                        vertical-align: middle
                    }

                    .WNN1b {
                        background-color: #202124
                    }

                    .W4XqN {
                        cursor: pointer;
                        background-color: #202124
                    }

                    .GKXWV {
                        border-top: 1px solid #5f6368;
                        height: 0;
                        margin-left: 5px;
                        margin-right: 5px
                    }

                    .eNRwyf {
                        height: 100%;
                        width: 100%
                    }

                    sentinel {
                    }

                    .pkWBse {
                        box-shadow: 1px 1px 15px 0px #171717
                    }

                    .pkWBse {
                        border-radius: 8px
                    }

                    .UjBGL {
                        display: block
                    }

                    .CcNe6e {
                        cursor: pointer;
                        display: inline-block
                    }

                    .iRQHZe {
                        position: absolute
                    }

                    .Qaqu5 {
                        position: relative
                    }

                    .shnMoc.CcNe6e {
                        display: block
                    }

                    .v4Zpbe.CcNe6e {
                        display: -webkit-box;
                        display: -webkit-flex;
                        display: flex;
                        height: 100%;
                        width: 100%
                    }

                    sentinel {
                    }

                    .PBn44e {
                        border-radius: 8px
                    }

                    .yTik0 {
                        border: none;
                        display: block;
                        outline: none
                    }

                    .wplJBd {
                        white-space: nowrap
                    }

                    .JM22S::-webkit-scrollbar {
                        width: 8px
                    }

                    .JM22S::-webkit-scrollbar-thumb {
                        background-color: #bababa;
                        border-right: 4px solid #fff
                    }

                    .iQXTJe {
                        padding: 5px 0
                    }

                    sentinel {
                    }

                    .Zt0a5e.LGiluc {
                        border-top-color: #3c4043
                    }

                    .Zt0a5e.LGiluc,.Zt0a5e.EpPYLd[disabled] {
                        color: rgba(255,255,255,0.26)!important
                    }

                    .CjiZvb,.GZnQqe.EpPYLd:active {
                        background-color: rgba(255,255,255,0.1)
                    }

                    .EpPYLd {
                        display: block;
                        position: relative
                    }

                    .YpcDnf {
                        padding: 0 16px;
                        vertical-align: middle
                    }

                    .YpcDnf.HG1dvd {
                        padding: 0
                    }

                    .HG1dvd>* {
                        padding: 0 16px
                    }

                    .WtV5nd .YpcDnf {
                        padding-left: 28px
                    }

                    .Zt0a5e .YpcDnf {
                        line-height: 48px
                    }

                    .GZnQqe .YpcDnf {
                        line-height: 23px
                    }

                    .EpPYLd:hover {
                        cursor: pointer
                    }

                    .EpPYLd,.CB8nDe:hover {
                        cursor: default
                    }

                    .LGiluc,.EpPYLd[disabled] {
                        pointer-events: none;
                        cursor: default
                    }

                    .LGiluc {
                        border-top: 1px solid;
                        height: 0;
                        margin: 5px 0
                    }

                    .Zt0a5e.CB8nDe {
                        background: no-repeat left 8px center
                    }

                    .Zt0a5e.CB8nDe {
                        background-image: url(https://ssl.gstatic.com/images/icons/material/system/1x/done_white_16dp.png)
                    }

                    .GZnQqe.CB8nDe {
                        background: no-repeat left center
                    }

                    .GZnQqe.CB8nDe {
                        background-image: url(https://ssl.gstatic.com/ui/v1/menu/checkmark2-light.png)
                    }

                    .GZnQqe.LGiluc,.GZnQqe.EpPYLd[disabled] {
                        color: #dadce0!important
                    }

                    .GZnQqe.LGiluc {
                        border-top-color: #3c4043
                    }

                    sentinel {
                    }
                </style>
                <script nonce="x9iHkhRHZETt-9nytNuh5g">
                    (function() {
                        google.tick("load", "sct");
                    }
                    ).call(this);
                </script>
                <div data-st-cnt="ee" id="easter-egg"></div>
                <style>
                    .yg51vc {
                        background: #202124;
                        height: 47px;
                        position: relative;
                        padding: 0;
                        z-index: 126;
                        white-space: nowrap;
                    }

                    .iJddsb {
                        display: inline-block;
                        fill: currentColor
                    }

                    .iJddsb img,.iJddsb svg {
                        display: block;
                        height: 100%;
                        width: 100%
                    }

                    .pdswFd {
                        float: right;
                        position: relative;
                        right: 17px;
                        z-index: 3
                    }

                    .pdswFd .hdtb-mitem {
                        display: inline-block
                    }

                    .fFI3rb {
                        padding: 13px 6px 8px 12px;
                        border-radius: 8px
                    }

                    .F75bid {
                        color: #969ba1;
                        display: inline-block
                    }

                    .NkCsjc {
                        position: relative;
                        display: block;
                        outline: none
                    }

                    .S7TGef {
                        font-size: 14px;
                        height: 24px;
                        line-height: 24px;
                        margin-right: 1px;
                        white-space: nowrap;
                        display: inline
                    }

                    .S7TGef,.BpGBNe {
                        font-weight: bold;
                        color: #bdc1c6
                    }

                    #lb .S7TGef,#lb .BpGBNe {
                        color: #4487f6
                    }

                    .NkCsjc:after {
                        content: '';
                        display: block;
                        clear: both
                    }

                    .MmOzS {
                        vertical-align: middle;
                        padding-bottom: 2px;
                        padding-left: 4px
                    }

                    .Lj8KXd {
                        background-color: transparent;
                        top: 0;
                        width: 100%;
                        white-space: nowrap;
                        height: 22px;
                        position: absolute;
                        -webkit-transition: top 220ms ease-in-out;
                    }

                    .p4DDCd {
                        display: none
                    }

                    .Bb1JKe {
                        padding-bottom: 8px
                    }

                    sentinel {
                    }

                    .ouy7Mc {
                        padding-left: 16px;
                        padding-right: 16px
                    }

                    sentinel {
                    }

                    .M8CEed {
                        padding-top: 12px
                    }

                    sentinel {
                    }

                    .gTMtLb {
                        z-index: 1001;
                        position: absolute;
                        top: -1000px
                    }

                    @keyframes ghost-card-shimmering {
                        0% {
                            transform: translateX(-100%)
                        }

                        100% {
                            transform: translateX(100%)
                        }
                    }
                </style>
                <div jscontroller="HYSCof" class="gke0pe" id="top_nav" jsdata="Z1JpA;_;Bmu0rg" jsaction="rcuQ6b:npT2md">
                    <h2 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Chế độ tìm kiếm</h2>
                    <div class="GLcBOb" role="navigation" id="hdtb">
                        <div class="yg51vc" id="pTwnEc">
                            <div class="IC1Ck" id="hdtb-msb">
                                <div>
                                    <div class="MUFPAc">
                                        <div class="hdtb-mitem hdtb-msel" aria-current="page">
                                            <span>
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path fill="#34a853" d="M10 2v2a6 6 0 0 1 6 6h2a8 8 0 0 0-8-8"></path>
                                                        <path fill="#ea4335" d="M10 4V2a8 8 0 0 0-8 8h2c0-3.3 2.7-6 6-6"></path>
                                                        <path fill="#fbbc04" d="M4 10H2a8 8 0 0 0 8 8v-2c-3.3 0-6-2.69-6-6"></path>
                                                        <path fill="#4285f4" d="M22 20.59l-5.69-5.69A7.96 7.96 0 0 0 18 10h-2a6 6 0 0 1-6 6v2c1.85 0 3.52-.64 4.88-1.68l5.69 5.69L22 20.59"></path>
                                                    </svg>
                                                </span>
                                                Tất cả<div class="YTDezd"></div>
                                            </span>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;tbm=isch&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_AUoAXoECAEQAw" data-hveid="CAEQAw">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M14 13l4 5H6l4-4 1.79 1.78L14 13zm-6.01-2.99A2 2 0 0 0 8 6a2 2 0 0 0-.01 4.01zM22 5v14a3 3 0 0 1-3 2.99H5c-1.64 0-3-1.36-3-3V5c0-1.64 1.36-3 3-3h14c1.65 0 3 1.36 3 3zm-2.01 0a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h7v-.01h7a1 1 0 0 0 1-1V5"></path>
                                                    </svg>
                                                </span>
                                                Hình ảnh
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;tbm=vid&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_AUoAnoECAEQBA" data-hveid="CAEQBA">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M10 16.5l6-4.5-6-4.5v9zM5 20h14a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1zm14.5 2H5a3 3 0 0 1-3-3V4.4A2.4 2.4 0 0 1 4.4 2h15.2A2.4 2.4 0 0 1 22 4.4v15.1a2.5 2.5 0 0 1-2.5 2.5"></path>
                                                    </svg>
                                                </span>
                                                Video
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;tbm=shop&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;source=lnms" data-hveid="CAEQBQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26tbm%3Dshop%26sxsrf%3DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411%26source%3Dlnms&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QiaAMKAN6BAgBEAU">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M21.11 2.89A3.02 3.02 0 0 0 18.95 2h-5.8c-.81 0-1.58.31-2.16.89L7.25 6.63 2.9 10.98a3.06 3.06 0 0 0 0 4.32l5.79 5.8a3.05 3.05 0 0 0 4.32.01l8.09-8.1c.58-.58.9-1.34.9-2.16v-5.8c0-.81-.32-1.59-.89-2.16zM20 10.85c0 .28-.12.54-.32.74l-3.73 3.74-4.36 4.36c-.41.41-1.08.41-1.49 0l-2.89-2.9-2.9-2.9a1.06 1.06 0 0 1 0-1.49l8.1-8.1c.2-.2.46-.3.74-.3l5.8-.01A1.05 1.05 0 0 1 20 5.05v5.8zM16 6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2"></path>
                                                    </svg>
                                                </span>
                                                Mua sắm
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;tbm=bks&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_AUoBHoECAEQBg" data-hveid="CAEQBg">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M18 2H6a2 2 0 0 0-2 2v16c0 1.1.9 2 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm0 18H6V4h2v8l2.5-1.5L13 12V4h5v16"></path>
                                                    </svg>
                                                </span>
                                                Sách
                                            </a>
                                        </div>
                                    </div>
                                    <span class="hdtb-mitem" jscontroller="nabPbb" data-ffp="false" jsaction="KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;">
                                        <g-popup jsname="V68bde" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;Bmu0r0">
                                            <div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" role="button" tabindex="0" jsaction="WFrRFb;keydown:uYT2Vb">
                                                <div jsname="LgbsSe" class="GOE98c">
                                                    <span class="MbEPDb z1asCe SaPW2b" style="height:16px;line-height:16px;width:16px">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                        </svg>
                                                    </span>
                                                    Thêm
                                                </div>
                                            </div>
                                            <div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:200" id="_WrGXZcTbGIHc1e8P9Y2o8A8_18"></div>
                                        </g-popup>
                                    </span>
                                </div>
                                <div>
                                    <div class="t2vtad" id="hdtb-tls" aria-controls="hdtbMenus" aria-expanded="false" role="button" tabindex="0" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2x96BAgBEA0">Công cụ</div>
                                </div>
                            </div>
                            <ol class="pdswFd" role="none">
                                <li class="hdtb-mitem">
                                    <div class="nr7I6e">
                                        <span jscontroller="nabPbb" data-ffp="false" jsaction="KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;">
                                            <g-popup jsname="V68bde" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;Bmu0r0">
                                                <div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" role="button" tabindex="0" jsaction="WFrRFb;keydown:uYT2Vb">
                                                    <div jsname="LgbsSe" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q7KcKegQIARAP">
                                                        <g-dropdown-button class="fFI3rb NkCsjc">
                                                            <g-dropdown-menu-button-caption class="S7TGef BBwThe" style="font-weight:normal" jscontroller="EbPKJf" data-ddph="" jsaction="rcuQ6b:npT2md">
                                                                <span jsname="vs0Yb">
                                                                    <div class="F75bid">
                                                                        Tìm kiếm an toàn
                                                                        <span class="MmOzS z1asCe K1bG5d" style="height:20px;line-height:20px;width:20px">
                                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                <path d="M7 10l5 5 5-5z"></path>
                                                                            </svg>
                                                                        </span>
                                                                    </div>
                                                                </span>
                                                            </g-dropdown-menu-button-caption>
                                                        </g-dropdown-button>
                                                    </div>
                                                </div>
                                                <div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:200" id="_WrGXZcTbGIHc1e8P9Y2o8A8_22"></div>
                                            </g-popup>
                                        </span>
                                    </div>
                                </li>
                            </ol>
                        </div>
                        <div class="Lj8KXd p4DDCd" data-st-cnt="stb" id="hdtbMenus" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q3B96BAgBEBc">
                            <div class="muaC1e" id="tn_1"></div>
                        </div>
                    </div>
                </div>
                <div id="before-appbar"></div>
                <div class="gTMtLb fp-nh" id="lb"></div>
                <div class="appbar" data-st-cnt="top" id="appbar">
                    <div data-st-tgt="top">
                        <style>
                            .WE0UJf.NyYcvd {
                                height: 43px
                            }

                            .LHJvCe {
                                color: #9aa0a6;
                                display: flex;
                                justify-content: space-between;
                                -webkit-transition: all 220ms ease-in-out;
                                line-height: 43px;
                                min-width: 652px;
                                position: absolute;
                                top: 0
                            }

                            #result-stats {
                                overflow: hidden;
                                text-overflow: ellipsis;
                                white-space: nowrap;
                                font-family: Google Sans,arial,sans-serif;
                                padding-top: 0;
                                padding-bottom: 0;
                                padding-right: 8px;
                            }

                            @keyframes loading-pulse {
                                from {
                                    opacity: 0.2
                                }

                                to {
                                    opacity: 1
                                }
                            }
                        </style>
                        <div id="extabar">
                            <div style="position:relative">
                                <div class="WE0UJf NyYcvd" id="slim_appbar">
                                    <div class="LHJvCe">
                                        <div id="result-stats">
                                            Khoảng 34.000.000 kết quả<nobr>(0,23 giây)&nbsp;</nobr>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div jscontroller="sYEX8b" jsname="GGAcbc" class="AeB7Sc" data-cssl="/setprefs?hl=vi&amp;prev=https://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp%26pccc%3D1&amp;sig=0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D&amp;cs=1" data-eif="1" data-escd="1" data-kulima="1" id="spic_1" aria-label="Cài đặt tìm kiếm" role="dialog" tabindex="-1" jsaction="rcuQ6b:npT2md;Lhx8ef:hZ2GLc;UVNdjb;keydown:mivSOc" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QzNQJegQIBhAB"></div>
                    </div>
                </div>
                <div id="_WrGXZcTbGIHc1e8P9Y2o8A8_9"></div>
                <div data-spl="/setprefs?hl=vi&amp;prev=https://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp%26pccc%3D1&amp;sig=0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D&amp;cs=1" id="YUIDDb" style="display:none"></div>
                <div data-iatvcap="1" data-st-cnt="atvcap" id="atvcap"></div>
                <div class="GyAeWb" id="rcnt">
                    <div class="s6JM6d" id="center_col">
                        <style>
                            .rsGxI.Ww4FFb,.Ww4FFb {
                                background-color: #202124;
                                border-radius: 0px;
                                border-width: 0px;
                                box-shadow: 0px
                            }

                            .Ww4FFb .mnr-c,.mnr-c .Ww4FFb,.Ww4FFb .Ww4FFb {
                                box-shadow: none;
                                margin-bottom: 0px
                            }

                            .vt6azd {
                                margin: 0px 0px 8px;
                                margin: 0px 0px 30px;
                            }

                            .tF2Cxc.asEBEc {
                                margin-bottom: 30px
                            }

                            .N54PNb {
                                position: relative
                            }

                            .cvP2Ce {
                                contain: layout paint;
                                overflow: hidden;
                            }

                            .kb0PBd {
                                display: block;
                                flex: 0 0 auto
                            }

                            .byrV5b {
                                -webkit-box-align: center;
                                -webkit-align-items: center;
                                align-items: center;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row
                            }

                            .sBJG1d {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row;
                                -webkit-box-pack: center;
                                -webkit-justify-content: center;
                                justify-content: center
                            }

                            .kDmHO {
                                -webkit-box-align: center;
                                -webkit-align-items: center;
                                align-items: center;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column
                            }

                            .lR4vec {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column;
                                -webkit-box-pack: center;
                                -webkit-justify-content: center;
                                justify-content: center
                            }

                            .xTEyc {
                                -webkit-box-align: start;
                                -webkit-align-items: start;
                                align-items: start;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row
                            }

                            .OjFzvd {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row;
                                -webkit-box-pack: start;
                                -webkit-justify-content: start;
                                justify-content: start
                            }

                            .YIPhrb {
                                -webkit-box-align: start;
                                -webkit-align-items: start;
                                align-items: start;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column
                            }

                            .BToiNc {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column;
                                -webkit-box-pack: start;
                                -webkit-justify-content: start;
                                justify-content: start
                            }

                            .E4bmEc .Va021 {
                                -webkit-box-flex: 1;
                                -webkit-flex: 1 1 100%;
                                flex: 1 1 100%
                            }

                            .E4bmEc .Y76LGf {
                                -webkit-box-flex: 1;
                                -webkit-flex: 1 1 calc(50% - 4px);
                                flex: 1 1 calc(50% - 4px)
                            }

                            sentinel {
                            }

                            a:hover h3.LC20lb {
                                text-decoration: underline
                            }

                            .M8OgIe .dG2XIf .fm06If .LC20lb,.n6SJS h3.LC20lb {
                                overflow: hidden;
                                text-overflow: ellipsis;
                                white-space: nowrap;
                                width: 100%
                            }

                            .LC20lb {
                                display: inline-block;
                                line-height: 1.3;
                                margin-bottom: 3px;
                            }

                            .DKV0Md {
                                padding-top: 4px;
                                padding-top: 5px;
                            }

                            .DKV0Md {
                                margin-top: 18px;
                            }

                            .VjDLd .TieM1d .tjvcx,.IVvPP .tjvcx,.kno-kp .tjvcx,.VjDLd .kp-wholepage-osrp .tjvcx,#rhs .ss6qqb .tjvcx,#rhs .trNcde .tjvcx {
                                display: inline-block;
                                height: 19px;
                                overflow-y: hidden
                            }

                            .TbwUpd.ojE3Fb {
                                display: flex;
                                padding: 0;
                                align-items: center;
                                padding-bottom: 0
                            }

                            .GvPZzd {
                                font-size: 12px;
                                line-height: 18px;
                            }

                            .VuuXrf {
                                color: #dadce0;
                                font-size: 14px;
                                display: block;
                                line-height: 20px;
                                white-space: nowrap;
                            }

                            .DDKf1c {
                                margin-right: 12px;
                            }

                            .UnOTSe img {
                                border: 1px solid #9aa0a6;
                                background-color: #fff;
                                border-radius: 50%;
                            }

                            .ob9lvb {
                                color: #bdc1c6
                            }

                            .ylgVCe {
                                color: #bdc1c6
                            }

                            .B6fmyf {
                                position: absolute;
                                top: 0;
                                height: 0;
                                visibility: hidden;
                                white-space: nowrap
                            }

                            .B6fmyf.Mg1HEd {
                                height: auto
                            }

                            .csDOgf {
                                display: inline;
                                visibility: visible
                            }

                            .csDOgf.BCF2pd.ezY6nb,.csDOgf.L48a4c {
                                height: 18px
                            }

                            .csDOgf {
                                margin-left: 8px;
                                position: relative
                            }

                            .csDOgf.L48a4c {
                                margin-top: 16px
                            }

                            .Vwoesf:not(.oRVWZ) {
                                display: inline-block
                            }

                            .Vwoesf {
                                vertical-align: middle
                            }

                            .XNo5Ab.XNo5Ab {
                                display: block
                            }

                            .lWlVCe {
                                border-radius: 50%
                            }

                            .bJVp8c {
                                color: #697988
                            }

                            .Jj3Uob {
                                color: #697988
                            }

                            sentinel {
                            }

                            .IjabWd {
                                margin-left: 2px
                            }

                            .xTFaxe {
                                top: 2px
                            }

                            .xTFaxe {
                                color: #9aa0a6
                            }

                            .D6lY4c {
                                height: 22px;
                                width: 22px;
                                position: absolute;
                                border-radius: 11px
                            }

                            .iTPLzd {
                                cursor: pointer;
                                top: 0;
                                line-height: 16px
                            }

                            .iTPLzd {
                                left: 0;
                                width: 28px
                            }

                            .iTPLzd {
                                z-index: 1
                            }

                            .GCkcpb {
                                cursor: pointer;
                                top: 0;
                                padding-bottom: 12px;
                                margin-left: 8px
                            }

                            sentinel {
                            }

                            .rNSxBe {
                                padding-bottom: 20px
                            }

                            sentinel {
                            }

                            .eY4mx {
                                padding-left: 12px
                            }

                            sentinel {
                            }

                            .lUn2nc {
                                padding-right: 12px
                            }

                            sentinel {
                            }

                            .yXK7lf em {
                                color: #bcc0c3
                            }

                            .yXK7lf a:visited em,.yXK7lf a em {
                                color: inherit
                            }

                            .hJNv6b {
                                padding-top: 0;
                                margin-bottom: 0
                            }

                            .r025kc.lVm3ye {
                                color: #bdc1c6
                            }

                            .Hdw6tb {
                                display: -webkit-box;
                                -webkit-box-orient: vertical;
                                overflow: hidden
                            }

                            .z3HNkc {
                                background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon fill='%2380868b' points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                background-repeat: repeat-x;
                                display: inline-block;
                                overflow: hidden;
                                position: relative
                            }

                            .z3HNkc span {
                                background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon fill='%23fdd663' points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                background-repeat: repeat-x;
                                display: block
                            }

                            .aNmOgc .z3HNkc span {
                                background-color: currentcolor;
                                background-image: unset;
                                -webkit-mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                -webkit-mask-repeat: repeat-x;
                                mask-repeat: repeat-x;
                                -webkit-mask-size: 14px 11.4px;
                                mask-size: 14px 11.4px
                            }

                            .z3HNkc.YMYLUd span {
                                background-color: currentcolor;
                                background-image: unset;
                                -webkit-mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                -webkit-mask-repeat: repeat-x;
                                mask-repeat: repeat-x;
                                -webkit-mask-size: 14px 11.4px;
                                mask-size: 14px 11.4px
                            }

                            .z3HNkc,.z3HNkc span {
                                background-size: 14px 11.4px;
                                height: 11.4px;
                                width: 68px
                            }

                            sentinel {
                            }

                            .HiHjCd {
                                color: #9aa0a6
                            }

                            .Sqrs4e {
                                padding-top: 0;
                                margin-bottom: 0
                            }

                            .LEwnzc {
                                color: #9aa0a6;
                            }
                        </style>
                        <div id="taw">
                            <div id="oFNiHe" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QL3oECAcQAg"></div>
                            <div id="tvcap"></div>
                        </div>
                        <div class="eqAnXb" id="res" role="main">
                            <div id="topstuff"></div>
                            <div id="search">
                                <div data-hveid="CAcQBA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QGnoECAcQBA">
                                    <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Kết quả tìm kiếm</h1>
                                    <div class="v7W49e" eid="WrGXZcTbGIHc1e8P9Y2o8A8" data-async-context="query:code%20m%E1%BA%ABu" id="rso">
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CBEQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIERAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_IdDnDe">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAoQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAoQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Bài tập C++ có lời giải (code mẫu)</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAQlBMVEVHcEz////////////////7+/v////Y0d6mlLWTfKZ9X5X///9NDHNFAG5TGnfs7ez7+vzHvdFXJXrq5+5qRIe1p8JFwjiIAAAAEXRSTlMAW5fA0iz//////6z///8T+ijYHSgAAAFkSURBVHgBZJJRluMgDAQdk2kAqzVIwP2vusCLk9mX/rMLgRB1fPI4w/MZzsfxlZ+AmHIpOUWEn//ZhSQUnRFKwvUH/VYTcRWuqItY/X0zJLqyWANqTCLOhJvWyaQ33EmctL7Oi3RmzMQxVjXWD7t2nxCXxQbpg+xtU8HqOQzRPlkpSUqjGw1IIilMCHXGyUSrsNOGrE93Ys4lchUaKRxA6yQdWEsexzlEBtAL8sCKtEhDo6bzCFkZUamqdcPUqRkQLeF4TtgQqeR9y91g1/58w4JkGzqMNwxpbdvoLnwVdrm3PW035BPGDLRRVGW8Gnq0fZVBzdZjTL3RCQwRm8+OvofQVdmjJaGL3UM4gu3S6uJqltWdDUM0hz34rpIAZLIYuaZZ6axblmudsmgdOaeYNQGd9lKlGl1Kw58w17cmRv1oMlnK+EhUW+ctmHjut2C3mtY/atbrS+o2ci55fEv9b9izAwDFrRvhRBwcqQAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">Quantrimang.com</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://quantrimang.com<span class="ylgVCe ob9lvb" role="text">› Học CNTT › Lập trình C++</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">Quantrimang.com</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://quantrimang.com<span class="ylgVCe ob9lvb" role="text">› Học CNTT › Lập trình C++</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sE cECq7c;_;Bmu0sM" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIChAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIChAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">Yêu cầu: Mỗi lần chỉ chuyển 1 tầng, chỉ được dùng các vị trí A, B, C để đặt các tầng tháp, không được đặt tầng lớn lên trên tầng nhỏ. Hàm main sử dụng hàm này ...</div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr">
                                                            <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 4,0 trên 5," role="img">
                                                                <span style="width:56px"></span>
                                                            </span>
                                                            <span>Xếp hạng: 4,1</span>
                                                            · ‎<span>57 phiếu bầu</span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="3" data-snf="gdePb">
                                                        <div class="HiHjCd">
                                                            ‎<a href="https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335#mcetoc_1c07r9mil1" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335%23mcetoc_1c07r9mil1&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAHoECA4QAQ">Bài tập C++ số 1</a>
                                                            · ‎<a href="https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335#mcetoc_1c07r9mil3" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335%23mcetoc_1c07r9mil3&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAXoECA4QAg">Bài tập C++ số 3</a>
                                                            · ‎<a href="https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335#mcetoc_1c07r9mil4" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335%23mcetoc_1c07r9mil4&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAnoECA4QAw">Bài tập C++ số 4</a>
                                                            · ‎<a href="https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335#mcetoc_1c07r9mil6" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335%23mcetoc_1c07r9mil6&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoA3oECA4QBA">Bài tập C++ số 6</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <span id="z9PoV"></span>
                                            <script nonce="x9iHkhRHZETt-9nytNuh5g">
                                                (function() {
                                                    var eid = 'z9PoV';
                                                    var a = google.c.frt
                                                      , b = google.c.frvt;
                                                    var c = Date.now()
                                                      , d = document.getElementById(eid);
                                                    b && google.c.mfrvt(c, d);
                                                    a && google.c.mfrt(c, d);
                                                    google.c.ub();
                                                    d && google.c.maft(c, d);
                                                }
                                                )();
                                            </script>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CA8QAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIDxAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_agf4xf">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAkQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAkQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">9 website cung cấp code mẫu tốt nhất dành cho lập trình viên</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAsVBMVEVHcEz1giD2gh71giD2gh31giDeuJ31giD2gh/1giD4gxv3gh33ghz1giD2gh/3gh71gh/1giD1giD1giD1giD1giD7hg/8hBPBdFXLd0oJUKAAOp4IRpsmU5wET6KYaW8ATKKPqdGZsNUMUaAARbOTaHG1bFWmYlq2bFTR0tTR0tTR0tTR0tTR0tTQ1NfMd0l2Yn7R0tTR0tTR0tTR0tTkfTPQ0tTR0tTR0tTR0dTR0tS594rlAAAAO3RSTlMAZ6rPtHYIIv/skYUu4fTFRKJaUBU8NdqM/1l0msDNgP///zkWnf+H/19v9K0YHP//qlD/PP86Jj8/zALgTjQAAAEtSURBVHgBdc8DgsRAFATQCrvi7bFtW/c/2PYYSV740cIHTTcM07KRQJCO6zmkj7iAIRQyQtyfFAAs0kIy3yEzaTVS4psX6gZuNIb4IUI6uMvmXpPgKf9YyCUF/GxGBsx9LpaHIqSHiNQlxdc5nkcvFL1CQQVfSuVKtVZvNOq1aqXcxLdGq9XutCrd67vVwI9efzCEMhw1e/gyhmKSxSLpvhJ3k+l4Nl8gWq5WZR3z+Xo8neBputnuthuguN9HwGZ72G6meFKl4xYKw1t4VIl38aTiOSBJD5ir4Pwurmfr2WQDj4qGzUTFazzZF8wBjTdZqOBi40uWZlaIrMkCYgrMP5sEfghm8aAxhy85anjx+FHIwaaHDzK8ZZWAFKHElygQpAMgMoxA4ocZGEaEfy4IGVclm8+0AAAAAElFTkSuQmCC" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">FUNiX</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://funix.edu.vn<span class="ylgVCe ob9lvb" role="text">› chia-se-kien-thuc › website-co...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">FUNiX</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://funix.edu.vn<span class="ylgVCe ob9lvb" role="text">› chia-se-kien-thuc › website-co...</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sI cECq7c;_;Bmu0sQ" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQICRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQICRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span class="LEwnzc Sqrs4e">
                                                                <span>4 thg 1, 2022</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                9 website cung cấp <em>code mẫu</em>
                                                                tốt nhất dành cho lập trình viên · 1. Stack Overflow · 2. SourceForge.net · 4. CodeProject.com · 5. DevX.com · 6.
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="3" data-snf="gdePb">
                                                        <div class="HiHjCd">
                                                            ‎<a href="https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/#1_stack_overflow" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/%231_stack_overflow&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAHoECA0QAQ">Stack Overflow</a>
                                                            · ‎<a href="https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/#2_sourceforgenet" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/%232_sourceforgenet&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAXoECA0QAg">SourceForge.net</a>
                                                            · ‎<a href="https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/#4_codeprojectcom" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/%234_codeprojectcom&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAnoECA0QAw">CodeProject.com</a>
                                                            · ‎<a href="https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/#5_devxcom" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/%235_devxcom&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoA3oECA0QBA">DevX.com</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CBAQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIEBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_M3zEFc">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://mikotech.vn/code-web-mau/" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAsQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://mikotech.vn/code-web-mau/&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECAsQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">10 Code web mẫu đẹp mắt, miễn phí các lập trình viên nên ...</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAJFBMVEVHcEwcwsEjxsMhxcMew8IgxMIhxcIfxMIkxsMcwsEbwcEgxMIgiirhAAAACHRSTlMAMSFEzumlZQZ5ezwAAACgSURBVCiRrdLLDsQgCAVQxBfI///vIFrbWrqYzNyV4cRQqAC/JMbwLMVxyI053400Vgqtqaar5Y6EC6WeVmhDltW30gNZpqF4ONtmD1mKNRT3JovOVoVeULShODeTYcqGZUNMMkNUwoYBZCnEB9YDg4N9iB4dyEHoX0N9FR7aHPCCuoLxb3w83sHfEK84NmTHpHh7QuMRzRJGhC1O6at8AI8fDHJ/Qb3nAAAAAElFTkSuQmCC" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">Miko Tech</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://mikotech.vn<span class="ylgVCe ob9lvb" role="text">› ✅️ Website đã xác minh</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">Miko Tech</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://mikotech.vn<span class="ylgVCe ob9lvb" role="text">› ✅️ Website đã xác minh</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sA cECq7c;_;Bmu0sU" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQICxAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQICxAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span class="LEwnzc Sqrs4e">
                                                                <span>27 thg 10, 2022</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                10 <em>code</em>
                                                                web <em>mẫu</em>
                                                                sau đây có thể giúp các lập trình viên cải thiện hiệu suất công việc và rút ngắn thời gian làm web chuyên nghiệp.
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="3" data-snf="gdePb">
                                                        <div class="HiHjCd">
                                                            ‎<a href="https://mikotech.vn/code-web-mau/#Code_Web_dong" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://mikotech.vn/code-web-mau/%23Code_Web_dong&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAHoECAwQAQ">Code Web động</a>
                                                            · ‎<a href="https://mikotech.vn/code-web-mau/#10_Code_web_mau_dep_mat_mien_phi_danh_cho_cac_lap_trinh_vien" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://mikotech.vn/code-web-mau/%2310_Code_web_mau_dep_mat_mien_phi_danh_cho_cac_lap_trinh_vien&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAXoECAwQAg">Code web mẫu đẹp mắt, miễn...</a>
                                                            · ‎<a href="https://mikotech.vn/code-web-mau/#4_Code_web_mau_Codeprojectcom" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://mikotech.vn/code-web-mau/%234_Code_web_mau_Codeprojectcom&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q0gIoAnoECAwQAw">Code web mẫu: Codeproject...</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <span class="oUAcPd" id="fld_1"></span>
                                            <script nonce="x9iHkhRHZETt-9nytNuh5g">
                                                (function() {
                                                    var id = 'fld_1';
                                                    document.getElementById(id).setAttribute("lta", Date.now());
                                                }
                                                )();
                                                (function() {
                                                    var eid = 'fld_1';
                                                    var a = Date.now()
                                                      , b = document.getElementById(eid);
                                                    if (b) {
                                                        var c = b.getAttribute("lta");
                                                        google.c.maft(c ? Number(c) : a, b)
                                                    }
                                                    ;
                                                }
                                                )();
                                            </script>
                                            <style>
                                                .ULSxyf {
                                                    margin-bottom: 44px
                                                }

                                                .hlcw0c {
                                                    margin-bottom: 44px
                                                }

                                                .H9lube {
                                                    background-color: #fff;
                                                    border: 1px solid #9aa0a6;
                                                    border-radius: 50%;
                                                    display: inline-flex;
                                                    justify-content: center;
                                                    align-items: center;
                                                    height: 26px;
                                                    width: 26px;
                                                    margin-right: 12px;
                                                    vertical-align: middle;
                                                }

                                                .eqA2re.NjwKYd {
                                                    margin-right: 0
                                                }

                                                .oIk2Cb {
                                                    margin: 0
                                                }

                                                .y6Uyqe {
                                                    margin-left: -8px;
                                                    margin-right: -8px;
                                                    padding: 6px 0 0 0
                                                }

                                                .kfsfbe.kfsfbe {
                                                    padding: 0 0 8px
                                                }

                                                .adDDi {
                                                    display: flex;
                                                    position: relative;
                                                    flex-wrap: wrap;
                                                    padding: 0 0 12px;
                                                    margin: 0 0
                                                }

                                                .T6zPgb {
                                                    min-width: 0
                                                }

                                                .YC72Wc {
                                                    max-width: calc(100% - 22px)
                                                }

                                                .mgAbYb {
                                                    display: block;
                                                    white-space: nowrap
                                                }

                                                .YR2tRd {
                                                    position: relative;
                                                    align-self: center;
                                                    height: 22px
                                                }

                                                .EIaa9b {
                                                    display: flex
                                                }

                                                .AJLUJb {
                                                    display: flex;
                                                    flex: 1;
                                                    flex-direction: column
                                                }

                                                .gduDCb {
                                                    margin-left: 12px
                                                }

                                                sentinel {
                                                }

                                                .k8XOCe {
                                                    align-items: center;
                                                    background-color: #303134;
                                                    border-radius: 100px;
                                                    box-sizing: border-box;
                                                    display: flex;
                                                    max-height: none;
                                                    min-height: 48px;
                                                    padding-left: 17px;
                                                    padding-right: 17px;
                                                    position: relative
                                                }

                                                .k8XOCe:hover,.k8XOCe:active {
                                                    color: #bdc1c6
                                                }

                                                .s75CSd {
                                                    -webkit-box-orient: vertical;
                                                    color: #bdc1c6;
                                                    display: -webkit-box;
                                                    flex: 1;
                                                    font-size: 16px;
                                                    -webkit-line-clamp: 2;
                                                    max-width: 227px;
                                                    overflow-wrap: break-word;
                                                    overflow: hidden
                                                }

                                                .aXBZVd {
                                                    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='rgba(255,255,255,.54)' d='M20.49 19l-5.73-5.73C15.53 12.2 16 10.91 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.41 0 2.7-.47 3.77-1.24L19 20.49 20.49 19zM5 9.5C5 7.01 7.01 5 9.5 5S14 7.01 14 9.5 11.99 14 9.5 14 5 11.99 5 9.5z'/%3E%3C/svg%3E");
                                                    background-position: center;
                                                    background-repeat: no-repeat;
                                                    background-size: 20px;
                                                    height: 20px;
                                                    padding: 10px;
                                                    width: 20px
                                                }

                                                .VCOFK {
                                                    margin-left: 8px;
                                                    margin-right: 8px
                                                }

                                                .R0xfCb {
                                                    margin-bottom: 4px;
                                                    margin-top: 4px
                                                }

                                                .s8bAkb {
                                                    padding-bottom: 0px;
                                                    padding-top: 0px
                                                }

                                                sentinel {
                                                }

                                                .unhzXb {
                                                    border-radius: 4px
                                                }

                                                sentinel {
                                                }

                                                .u60jwe {
                                                    margin-right: 0px
                                                }

                                                sentinel {
                                                }

                                                .z1asCe.kQdGHd,.WqQeqc.kQdGHd {
                                                    position: absolute
                                                }

                                                .WZH4jc {
                                                    text-align: center
                                                }

                                                .WZH4jc .VknLRd {
                                                    pointer-events: none
                                                }

                                                .WZH4jc .VknLRd:hover,.WZH4jc .VknLRd:hover h3 {
                                                    text-decoration: none
                                                }

                                                .WZH4jc .GNJvt {
                                                    background: #303134;
                                                    border: 1px solid rgba(255,255,255,0);
                                                    box-sizing: border-box;
                                                    cursor: pointer;
                                                    font-size: 14px;
                                                    line-height: 20px;
                                                    pointer-events: auto;
                                                    position: relative;
                                                    width: 300px;
                                                    padding: 7px 11px;
                                                    margin: 0;
                                                    flex-direction: row-reverse;
                                                    align-items: center;
                                                    display: flex;
                                                    justify-content: center;
                                                    margin-left: auto;
                                                    margin-right: auto;
                                                    height: 36px;
                                                    border-radius: 18px
                                                }

                                                .WZH4jc .VknLRd:hover .GNJvt {
                                                    background: #3c4043
                                                }

                                                .WZH4jc .kQdGHd {
                                                    position: relative;
                                                    left: 0
                                                }

                                                .WZH4jc .OTvAmd {
                                                    display: block
                                                }

                                                .WZH4jc .RVQdVd {
                                                    line-height: 20px;
                                                    margin-right: 8px
                                                }

                                                .KXbwLb {
                                                    background-color: #3c4043;
                                                    border: 0;
                                                    height: 1px;
                                                    left: 0;
                                                    margin-top: 18px;
                                                    position: absolute;
                                                    width: 100%
                                                }

                                                .QjmzCd {
                                                    text-align: center;
                                                    margin: 25px 0;
                                                    height: 30px
                                                }

                                                .w7LJsc {
                                                    height: 45px;
                                                    margin-bottom: 28px
                                                }

                                                .GNJvt {
                                                    display: block;
                                                    background-color: #303134;
                                                    text-align: center;
                                                    font-size: 14px;
                                                    color: #bdc1c6;
                                                    border-radius: 20px;
                                                    height: 24px;
                                                    line-height: 24px;
                                                    border: 1px solid rgba(255,255,255,0);
                                                    padding: 8px 13px;
                                                    margin: 16px 16px 40px 16px;
                                                }

                                                .RVQdVd {
                                                    line-height: 24px
                                                }

                                                .kQdGHd {
                                                    color: #9aa0a6;
                                                    left: 13px;
                                                    position: absolute
                                                }

                                                .GNJvt:active {
                                                    background: #3c4043
                                                }

                                                .VknLRd {
                                                    -webkit-tap-highlight-color: transparent;
                                                    display: block
                                                }

                                                .ipz2Oe {
                                                    position: relative
                                                }
                                            </style>
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CCwQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQILBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_lVEHBb">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB0QAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB0QAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Bài tập C++ có giải (code mẫu) về biến, kiểu dữ liệu và ...</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAQlBMVEVHcEz////////////////7+/v////Y0d6mlLWTfKZ9X5X///9NDHNFAG5TGnfs7ez7+vzHvdFXJXrq5+5qRIe1p8JFwjiIAAAAEXRSTlMAW5fA0iz//////6z///8T+ijYHSgAAAFkSURBVHgBZJJRluMgDAQdk2kAqzVIwP2vusCLk9mX/rMLgRB1fPI4w/MZzsfxlZ+AmHIpOUWEn//ZhSQUnRFKwvUH/VYTcRWuqItY/X0zJLqyWANqTCLOhJvWyaQ33EmctL7Oi3RmzMQxVjXWD7t2nxCXxQbpg+xtU8HqOQzRPlkpSUqjGw1IIilMCHXGyUSrsNOGrE93Ys4lchUaKRxA6yQdWEsexzlEBtAL8sCKtEhDo6bzCFkZUamqdcPUqRkQLeF4TtgQqeR9y91g1/58w4JkGzqMNwxpbdvoLnwVdrm3PW035BPGDLRRVGW8Gnq0fZVBzdZjTL3RCQwRm8+OvofQVdmjJaGL3UM4gu3S6uJqltWdDUM0hz34rpIAZLIYuaZZ6axblmudsmgdOaeYNQGd9lKlGl1Kw58w17cmRv1oMlnK+EhUW+ctmHjut2C3mtY/atbrS+o2ci55fEv9b9izAwDFrRvhRBwcqQAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">Quantrimang.com</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://quantrimang.com<span class="ylgVCe ob9lvb" role="text">› Học CNTT › Lập trình C++</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">Quantrimang.com</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://quantrimang.com<span class="ylgVCe ob9lvb" role="text">› Học CNTT › Lập trình C++</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sg cECq7c;_;Bmu0tE" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIHRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIHRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span class="LEwnzc Sqrs4e">
                                                                <span>15 thg 5, 2023</span>
                                                                — 
                                                            </span>
                                                            Bài tập C++ về toán tử · Viết một chương trình trong C++ để in tổng của hai số. · Tìm tổng, hiệu, tích và thương của hai số nguyên và in kết quả ...
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr">
                                                            <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 4,0 trên 5," role="img">
                                                                <span style="width:56px"></span>
                                                            </span>
                                                            <span>Xếp hạng: 3,9</span>
                                                            · ‎<span>35 phiếu bầu</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDIQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIMhAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_so0s7c">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECCEQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECCEQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho ...</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAATlBMVEVHcEwzMTIzMTIzMTIzMTIzMTIzMTIzMTIzMTIzMTIzMTIzMTIzMTIyMTIzMTIzMTIrLDNzWSUhJzNTRSr7sQDanAmugBbLkw+Ubx3uqQEN3e7wAAAAEHRSTlMASNWWESu7/+1tmXGy+oiOeEwUtAAAAMZJREFUeAG90wUSg0AQBMAog7OG/f+juQsOWynPliDN+XDb1/3xfN38eicA0syjV46pHveLFSnWKt+nwbCvqt6Gfpc41zL0q6nogjQPXQCMI5OwIo2YEVvLsmPRzlqZUVuzXhcmDKONA00IovjYqUQiDp/G+xkBQff9mkT70EscZMXI8W3L4Zt2oEB7XPoLvUOAPS7cWauBPISw9cF8pL9h8QvDkTlYLWl5lxdMs3NMFowxuQRswfLtRnPgJR9OqIn8UHu/wwfcAxanj6YU9gAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">YBOX</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://ybox.vn<span class="ylgVCe ob9lvb" role="text">› ky-nang › toptip-top-10-website-code...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">YBOX</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://ybox.vn<span class="ylgVCe ob9lvb" role="text">› ky-nang › toptip-top-10-website-code...</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sw cECq7c;_;Bmu0tA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIIRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIIRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span>
                                                                [TopTip] Top 10 Website <em>Code Mẫu</em>
                                                                Chuyên Nghiệp Cho Các Lập Trình Viên · 1. Stackoverflow.com · 2. Sourceforge.net · 3. CodeGuru.com · 4. Codeproject.com · 5.
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDEQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIMRAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_wqBfdd">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://api.tphcm.gov.vn/ChiTietLgsp/id/224" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBwQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://api.tphcm.gov.vn/ChiTietLgsp/id/224&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBwQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Code Example</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="H9lube">
                                                                                <div class="eqA2re NjwKYd Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAB90lEQVR4Ad3VA4wecRAF8Kltu8Ghtm27Deugtt04DWtbQe02/OKkZnS27bvdnb45a3HaD//kl43fW81Q4vgZXEMaZEAgvIcjn0ZNGNnP26fpnH4DSBge60HWJI+fod4aPiZyRr/+jxE+B6SIrQX46rAxPLPfAEZwKtyBfkBgd4Fi/2Ax1AenFBAxsK64hBMKiDhYBQROKSD8YQQQOKWAeAmtnVkgG9ZWrcC46Zw4ZqqpZLg2ZATP9vHluQbmefs4Fvbt04GshifNX85pew5z2t4jhjL3HeFz67bz0AXreMTC9bqGL9qY3m/NkVXWCuCuJFzLymbOUyBPn6Lw6e+JTHeDud59A/fkGvLQegHcnQRYOad+pzI9CGd6aCqkbgr8SrFaQHV2AfbIAtrB78l5TiuQo2rqYkd8ltMKfE3Ize38NNI5TyA+W1WWOuKzrYZDHKUgwIyM1wz9Alquyuo33LmE138YrlkMF+/oBhaHqSEj+cK67fkTToaMfOWnf4tUPvg9RZF3rvvY9eXAZpKtZUYWyzDM9noYrwjR97BKfkNfkvVoRraXLBDMcOsBxjQ4DOSsAl+gp7MKJMFSIGcUyIGj0BAIx9YCEn4GmheH21ggCY5WCLehgApfYWmZx25DgVz4A0egB5DAqfMCcfAetkAfqAdkdP4DRHovv+wXA+0AAAAASUVORK5CYII=" style="height:18px;width:18px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">tphcm.gov.vn</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://api.tphcm.gov.vn<span class="ylgVCe ob9lvb" role="text">› ChiTietLgsp</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="H9lube">
                                                                            <div class="eqA2re NjwKYd" style="height:18px;width:18px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">tphcm.gov.vn</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://api.tphcm.gov.vn<span class="ylgVCe ob9lvb" role="text">› ChiTietLgsp</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0so cECq7c;_;Bmu0s0" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIHBAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIHBAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span>
                                                                CODE EXAMPLE. <em>Code mẫu</em>
                                                                .Net. using RestSharp;. using System;. using System.Collections.Generic;. using System.Configuration;. using System.Linq;.
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDAQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIMBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_l77cVd">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://api.tphcm.gov.vn/ChiTietLgsp/id/117" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBsQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://api.tphcm.gov.vn/ChiTietLgsp/id/117&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBsQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Code mẫu .Net</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="H9lube">
                                                                                <div class="eqA2re NjwKYd Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAB90lEQVR4Ad3VA4wecRAF8Kltu8Ghtm27Deugtt04DWtbQe02/OKkZnS27bvdnb45a3HaD//kl43fW81Q4vgZXEMaZEAgvIcjn0ZNGNnP26fpnH4DSBge60HWJI+fod4aPiZyRr/+jxE+B6SIrQX46rAxPLPfAEZwKtyBfkBgd4Fi/2Ax1AenFBAxsK64hBMKiDhYBQROKSD8YQQQOKWAeAmtnVkgG9ZWrcC46Zw4ZqqpZLg2ZATP9vHluQbmefs4Fvbt04GshifNX85pew5z2t4jhjL3HeFz67bz0AXreMTC9bqGL9qY3m/NkVXWCuCuJFzLymbOUyBPn6Lw6e+JTHeDud59A/fkGvLQegHcnQRYOad+pzI9CGd6aCqkbgr8SrFaQHV2AfbIAtrB78l5TiuQo2rqYkd8ltMKfE3Ize38NNI5TyA+W1WWOuKzrYZDHKUgwIyM1wz9Alquyuo33LmE138YrlkMF+/oBhaHqSEj+cK67fkTToaMfOWnf4tUPvg9RZF3rvvY9eXAZpKtZUYWyzDM9noYrwjR97BKfkNfkvVoRraXLBDMcOsBxjQ4DOSsAl+gp7MKJMFSIGcUyIGj0BAIx9YCEn4GmheH21ggCY5WCLehgApfYWmZx25DgVz4A0egB5DAqfMCcfAetkAfqAdkdP4DRHovv+wXA+0AAAAASUVORK5CYII=" style="height:18px;width:18px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">tphcm.gov.vn</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://api.tphcm.gov.vn<span class="ylgVCe ob9lvb" role="text">› ChiTietLgsp</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="H9lube">
                                                                            <div class="eqA2re NjwKYd" style="height:18px;width:18px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">tphcm.gov.vn</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://api.tphcm.gov.vn<span class="ylgVCe ob9lvb" role="text">› ChiTietLgsp</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0tI cECq7c;_;Bmu0tQ" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIGxAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIGxAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span>
                                                                API đồng bộ thông tin đăng ký kết hôn. Code example. <em>Code mẫu</em>
                                                                .Net. API Method Get. API Method POST. <em>Code mẫu</em>
                                                                java. API Method Get. API Method POST. Danh sách ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDQQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQINBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_BlrVWd">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://didongviet.vn/dchannel/cach-lam-code-trai-tim/" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB8QAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://didongviet.vn/dchannel/cach-lam-code-trai-tim/&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB8QAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">10+ cách làm code trái tim của Thủ Khoa Lý cực kỳ đơn giản</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAA21BMVEXAAQu9BAy+AQ/FABPDAQ7FAA3BAQ7BAQfIAAmuAACkAACiAACpAAC7ABC4AATWV1vfqq3dq7XdrrTZXWfijJbhoqfie4LMSFOzABb/y87/9/b/9Pv//P7Yf4v/y9b/5uf+3d7vvcCvPUb/7fL//////fz///y/go//+fT0dH7HgZDmhpHYa3z+tMH/6/KvAArttb3MXmrhVWDCIjPWQE/zy8vAQ0adAACzAAazAACpByLFa3nZjY7AYGj7oab/0+LMVmngb3Lzy8aNAAD6hY3eg4P/xM+3TVbGJSgXx7eTAAABxklEQVR4AVXShaKqQBCA4WGTthWXtYFrd5zuev8nurO2v+1HDwAWoZQSMDHGOOdMYMxkEP85/EDZIz4OKARImwMx4QqX1QxSBlI6LuZ5nus7vu8ElAqAA8rQz+ULhaKpVK5Ua15EGIAQAhGcXF3FmFK60Yxb7U7X5wxwZaDCcis9nWBplvxrplnW7w1cQmGf5RXiNMMQh020fi8eRYJLg+SAqtVut8eTllL9TE+rM7hCNV+UlsvVulpo97M02WxDadSgTlqL3d39/d1s9vC4USrtP93BBdulO8aIRYIgeu7pLJuvrCtc3jMSEEFptHvBg2/W7m8Q1woIJeR+rRP9+uZc4x0hJKBYuDK4cMLz0eKa5pKYglWy3+wNSonzESTw3/GKdFahvMI7DmBzEkQP9TTrP83AvjqVGR4PF7MoqiiVfWwdecHp8+fOcx1/1y0oFU+rToiIGdRx8wVbftVbvUTHkxngEQCzpZ9XSaK1TlM9bCZZP+193VsH5Lbz3TrMGof9Y4b960s4DJvz8O/p6jYZ1aIZMWKQcrjzze21wwPysTtCD4bIOAOCl5VYlgWMAb5fkpwJIoQ4TN7oheUeCRoGArPO+h+/mzfcAMjhHgAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">Didongviet.vn</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://didongviet.vn<span class="ylgVCe ob9lvb" role="text">› Dchannel › Công nghệ</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">Didongviet.vn</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://didongviet.vn<span class="ylgVCe ob9lvb" role="text">› Dchannel › Công nghệ</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0tM cECq7c;_;Bmu0tU" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIHxAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIHxAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span class="LEwnzc Sqrs4e">
                                                                <span>13 thg 12, 2022</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                <em>Code mẫu</em>
                                                                trái tim cơ bản. Đây chính là những dòng code trước tiên nổi rần rần trên cộng đồng mạng khi phim đã ra mắt tập đầu tiên. Cụ thể, hình ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr">
                                                            <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 5,0 trên 5," role="img">
                                                                <span style="width:70px"></span>
                                                            </span>
                                                            <span>Xếp hạng: 5</span>
                                                            · ‎<span>1 phiếu bầu</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CC8QAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQILxAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_TLXAjc">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://codelearn.io/sharing/vong-lap-game-cac-code-mau" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB4QAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://codelearn.io/sharing/vong-lap-game-cac-code-mau&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECB4QAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Vòng Lặp Game - Các Code Mẫu</h3>
                                                                        <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                            <span class="H9lube">
                                                                                <div class="eqA2re NjwKYd Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAADy0lEQVR4Ab3XBZIUWRQF0FkCS2ApvYTeAe4OKei4u0vYuLv7TCIhuDvtbuVeNI/7L8Wrnx8oSeRFXGjPE08qoh4SkVi2+n0Ltvl9j27zr5zw/Mti4vuXkItM4F9AzkvInJPt/llhvDOywzvN7PROISdlF3MCOS67mWOZPd7RH5Cem8+LPXyLP9C71e/PACHbmCsEMC0Q4Z0QDBFMAyF7mKOvxgCb/cEFW/zBQSAECKaBYBSBKIIhglGEQtoiei3A0GYgBAixEXY3Oh6Jd1YRbUYSKWCTP/woEIIoAmmBSDaSXU43LMDID0AAgCgC6XIkYYuR3G4vFLDRH42AECAYdkMR92svbEAwFgEhNmLHwyOyd39OrvSV5bMvZxLtxVdfjkl/X1EO7JuTR/ecd/eiCdgAACIbg1HZaBDI5b6KmDp0pCBvvTvp7EVnp/reu0Ny5EhGTI2Pl929sAHjESJNxKigiNh8D0Zy9kxOTLkjUcD6YCJaT4AiFGDvRdJT7cMYTLmnqoB1wWQEhCCKmEtdNQAdCRHJTpWAVKrmnqoNmIqAkPUMEXh4VUrleR0JEQlPtVyeJ8I9VQWsDaYjIOQm4uFnpvHwazI6XovtxfOvTEq0P6fd2PHwMJY0LzsfHlLEvv0ZeemVkRhifLxCxDNP91lX4gAQMYhf/y4IioDX3p2194IdMfXdT2kiTp8pCQr/F9mJH36aFRQfZo/knXe5U6y//ppVhALWBDMAzIhBPPzMrHz8VZaAk2crsb349Ks0uxI+PGZGgo5MyNh4VV7A/xiH6QRfNz7/cjq2F2fOFIj64stJefrpfl1OCzAbASENBHOpr0axtRcKcfei3amiACu5p9oErA7mIiCEaSBGx+tEWMuJ3BnR4lTZlVSq7l6JDUhFQAiiCBQBXE6GCEYRCBGtT5UAU+6pKmBVkI5WBSmxESjsQJXdaIXQbrRAmCVF2XsRB6wMMhEQQkQDMpea5yJ++FVe9jwzZ0EmO96Lx58ek8++nOUCYgTu60UcgIiNePLVjIxgD0z98neRAAuBtN+L3//KCoojePGVcfclvAlYEWQByIoiEHck9pW03ou2I1GIBchFQEg3CEQRSU9VAcuD/AkgBFGEOxJFMC4i0alagLAgQACAEHJrN1YnHUmLU+XDl4XFHkQaCIaILkeS4FRPELA0LD1qAIxBhF0jkER70dMAlE8AIcsQRSCKYO75Xtx4a7YkrCxEZElYFiAYIpD7sBcREB8AsVDfnC4Oq48uCavSRJSjxkh6Eb6LvZ8BoDaIfABIL7/4gHMdL9ly/q4r38MAAAAASUVORK5CYII=" style="height:18px;width:18px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">CodeLearn</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://codelearn.io<span class="ylgVCe ob9lvb" role="text">› vong-lap-game-cac-code-mau</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                        <span class="H9lube">
                                                                            <div class="eqA2re NjwKYd" style="height:18px;width:18px"></div>
                                                                        </span>
                                                                        <div class="GTRloc">
                                                                            <span class="VuuXrf">CodeLearn</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://codelearn.io<span class="ylgVCe ob9lvb" role="text">› vong-lap-game-cac-code-mau</span>
                                                                                </cite>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0ss cECq7c;_;Bmu0s8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIHhAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIHhAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                            <span class="LEwnzc Sqrs4e">
                                                                <span>30 thg 1, 2021</span>
                                                                — 
                                                            </span>
                                                            Một vòng lặp trò chơi cần hai mảnh khóa cần để tâm: không chặn đầu vào người dùng và khả năng thích nghi với sự trôi dạt của thời gian. Đầu vào ...
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr">
                                                            <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 5,0 trên 5," role="img">
                                                                <span style="width:70px"></span>
                                                            </span>
                                                            <span>4 phiếu bầu</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="hlcw0c">
                                            <div class="MjjYud">
                                                <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDMQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFSgAegQIMxAA">
                                                    <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_HxVbQe">
                                                        <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                            <div class="yuRUbf">
                                                                <div>
                                                                    <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                        <a jsname="UWckNb" href="https://writeblabla.com/blog/tags/code-mau/" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBoQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://writeblabla.com/blog/tags/code-mau/&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QFnoECBoQAQ">
                                                                            <br>
                                                                            <h3 class="LC20lb MBeuO DKV0Md">code mẫu - Phan Tấn Dũng Blog</h3>
                                                                            <div class="notranslate TbwUpd YmJh3d NJjxre iUh30 ojE3Fb">
                                                                                <span class="DDKf1c">
                                                                                    <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                        <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAABDlBMVEX/6NH/7NX/6dL/7dbgtqPvzbj/89vDhnWSHw3/8dn328XFjHyfQzWOFACQIhamUkXPnIrLloWIAACNGxCUKhyPGALmwKytUTjEcE+dOSe7ZEbdjmT5q3T3rXuvVDvMelb5r32hSj777eX8+/z0qnnzuZeYKxe8f3GVMCavZlnwom7639DbzspSNCu6rKjDrKQgAADv7e32to6YOC+BaGEAAACSfHUQAACvTzGhPyvMv7vknG7k4N/98+zypn32xKfwlGfznnP2jW70e2XIg1rXlmSxmUyVnzqOqzuQdiWoV0mdkz2Rpjuxq2eTlTeHoiPMypGYZTCVTyWHmUDa0aKXQyaOiDqotF2VdTOLiiK4BznpAAABlElEQVR4AXWRBWOEIBiGCXXiDccBdiu37u7u7vj/f2RXa/fSPMQX4IcgAv8KazqsJwgb+oBpEFxzm1iNQWradIgB+Ic1ORVSSltQxyW/2AD3fD+wheeHkrs/7kKXR3EcJ2mWt4eUAvRlCTEKPymrUiVJq6r0eJi17eoxNDI6xscnJqemrfHxamZ2bj5bGBttdCkZC1UYxOXi0vJEG64sTbYiHqnVDkWA53m41n5vvZrfGLc2J7fGN/hGohY6NkOe5KHMx7d31MbSVNza2d1r38w3ig7EzeFsTWzsHygV5Umk1P5+KMLI6flDtJERKseVUhuHh6qtSJhsRMd9L7FRmHam8rbU0fHJ6VnDwF9xQOCcmyLw0vTi9PTy8gr/TAnRxii3xXWbndzc/k4MJMg6l3f39w+XN49/s4aMwH66ez69vAE1EFD75OH65PQF1qSbOfLpNXi7rLmIm9w0HSEeDVxzkeqMsbGhBcnwX1iMWFrhMN3l1p93O56MaZgZhq3XWEsIhliOnY9iUC8EGEMI/Ech/GTvSZwv0+mCj6IAAAAASUVORK5CYII=" style="height:26px;width:26px" alt="">
                                                                                    </div>
                                                                                </span>
                                                                                <div class="GTRloc">
                                                                                    <span class="VuuXrf">writeblabla.com</span>
                                                                                    <div class="byrV5b">
                                                                                        <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                            https://writeblabla.com<span class="ylgVCe ob9lvb" role="text">› Blog › Tags</span>
                                                                                        </cite>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                            <span jscontroller="IX53Tb" jsaction="rcuQ6b:npT2md" style="display:none"></span>
                                                                        </a>
                                                                    </span>
                                                                    <div class="B6fmyf byrV5b Mg1HEd">
                                                                        <div class="TbwUpd YmJh3d iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                            </span>
                                                                            <div class="GTRloc">
                                                                                <span class="VuuXrf">writeblabla.com</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://writeblabla.com<span class="ylgVCe ob9lvb" role="text">› Blog › Tags</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="csDOgf BCF2pd ezY6nb L48a4c">
                                                                            <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" data-movewtractions="true" jsdata="l7Bhpb;_;Bmu0sk cECq7c;_;Bmu0s4" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIGhAJ">
                                                                                <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                    <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                        <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                                <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                            </svg>
                                                                                        </span>
                                                                                    </span>
                                                                                </div>
                                                                                <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIGhAK"></span>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                            <div class="VwiC3b yXK7lf lVm3ye r025kc hJNv6b Hdw6tb" style="-webkit-line-clamp:2">
                                                                <span>
                                                                    Các bài viết hướng dẫn <em>code mẫu</em>
                                                                    các mẫu <em>code mẫu</em>
                                                                    đơn giản cần cho tất cả các lập trình viên.
                                                                </span>
                                                            </div>
                                                        </div>
                                                        <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                            <div class="fG8Fp uo4vr"></div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="bottomads"></div>
                        <div id="botstuff">
                            <div data-hveid="CAQQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QCHoECAQQAA">
                                <div>
                                    <div data-sstk="Aad95RoDvLNc9nlhpQhy6Nq4Nq8DOsK-kISdGNZtjuWN42VdUHTsvWdq5cpqst6L6TBJSdxTAVoOIJZzUfMjXwYPcC1BPuW8ONBwEA"></div>
                                </div>
                                <div id="bres">
                                    <div class="ULSxyf">
                                        <div class="MjjYud">
                                            <div data-abe="" data-hveid="CBYQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q26YDegQIFhAA">
                                                <div class="oIk2Cb">
                                                    <div class="kfsfbe adDDi">
                                                        <div class="T6zPgb YC72Wc">
                                                            <div aria-level="2" role="heading">
                                                                <span class="mgAbYb OSrXXb RES9jf IFnjPb">Nội dung tìm kiếm khác</span>
                                                            </div>
                                                        </div>
                                                        <span class="YR2tRd">
                                                            <div jscontroller="exgaYe" data-bsextraheight="0" data-darkmode="true" data-isdesktop="true" jsdata="l7Bhpb;_;Bmu0sY cECq7c;_;Bmu0sc" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q2esEegQIFhAC">
                                                                <div jsaction="KyPa0e:RvIhPd;wjOG7e:edHC5b;al5F3e:edHC5b;">
                                                                    <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc eY4mx" style="padding-right:5px;position:absolute" aria-label="Thông tin về kết quả này">
                                                                        <span jsname="czHhOd" class="D6lY4c IjabWd">
                                                                            <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px">
                                                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                    <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                </svg>
                                                                            </span>
                                                                        </span>
                                                                    </div>
                                                                    <span jsname="zOVa8" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh-4GegQIFhAD"></span>
                                                                </div>
                                                                <g-snackbar jsname="t1F84b" jscontroller="OZLguc" style="display:none" jsshadow="" jsaction="rcuQ6b:npT2md">
                                                                    <div jsname="sM5MNb" aria-live="polite" class="LH3wG">
                                                                        <div jsname="Ng57nc" class="yK6jqe" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4G96BAgWEAQ">
                                                                            <div class="b77HKf">
                                                                                <div class="rIxsve" jsslot="">
                                                                                    <span class="Txngnb wHYlTd yUTMj">Giờ đây, bạn sẽ thấy nhiều nội dung tiếng Anh hơn.</span>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </g-snackbar>
                                                            </div>
                                                        </span>
                                                    </div>
                                                    <div class="y6Uyqe">
                                                        <div class="EIaa9b">
                                                            <div class="AJLUJb">
                                                                <div data-hveid="CCAQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Web+code+m%E1%BA%ABu&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAggEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Web</b>
                                                                            code mẫu
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CCQQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Code+m%E1%BA%ABu+C%2B%2B&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgkEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Code</b>
                                                                            mẫu <b>C++</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CCUQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Code+m%C3%A0u+c+tr%C3%A1i+tim&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAglEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Code màu c trái tim</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CCMQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Share+code+web+HTML+%C4%91%E1%BA%B9p+free&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgjEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Share</b>
                                                                            code <b>web HTML đẹp free</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                            </div>
                                                            <div class="AJLUJb">
                                                                <div data-hveid="CCIQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Code+m%C3%A0u+tr%C3%A1i+tim&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgiEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Code màu trái tim</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBkQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=B%C3%A0i+t%E1%BA%ADp+code+C%2B%2B&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgZEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Bài tập</b>
                                                                            code <b>C++</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBgQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=B%C3%A0i+t%E1%BA%ADp+code+C+c%C3%B3+b%E1%BA%A3n&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgYEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Bài tập</b>
                                                                            code <b>C có bản</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBcQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;q=Share+code+web+HTML+%C4%91%C6%A1n+gi%E1%BA%A3n&amp;sa=X&amp;ved=2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q1QJ6BAgXEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Share</b>
                                                                            code <b>web HTML đơn giản</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div jscontroller="ogmBcd" jsname="BRTknd" jsmodel="oWVrne" class="sdjuGf" jsdata="A7MAsf;_;Bmu0rs" jsaction="rcuQ6b:npT2md;Jl3rxb:VimORe;BqPbQ:p5vRo;Kf5VV:CYKeQe;lQkSke:fj32se;aLHH2d:XV6jYd;LYjNec:cyaZJ;QEvNdb:teMyNc;K6ldnc:vK2xWc;xHsTDe:PoQGh">
                                    <div jscontroller="Gg40M" jsaction="rcuQ6b:npT2md;yFBEId:dNTL7c;AnqxQb:dNTL7c;aLHH2d:yTpwFc">
                                        <div jsname="TCyEnb" aria-owns="rhs"></div>
                                        <div jsname="nZDdGd" tabindex="0"></div>
                                    </div>
                                    <div jsname="sgxt2d" data-graft-type="insert" id="arc-srp_1" data-jiis="up" data-async-type="arc" data-async-context-required="arc_id,q" class="yp" data-async-rclass="search" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QxK8CegQIBBAC"></div>
                                    <div jsname="GDPwke" class="WtZO4e"></div>
                                    <div class="WZH4jc w7LJsc" jscontroller="bpec7b" data-dt="1" jsaction="AnqxQb:eFvKib;q8sV4d:eFvKib;Rlvoif:eFvKib;yFBEId:eFvKib">
                                        <div jsname="b6rISd" class="QjmzCd" style="display:none" role="progressbar" aria-label="Đang tải..." aria-live="polite" data-hveid="CAQQAw" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q66oDegQIBBAD"></div>
                                        <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Page Navigation</h1>
                                        <a class="T7sFge sW9g3e VknLRd" href="/search?q=code+m%E1%BA%ABu&amp;sca_esv=595895911&amp;sxsrf=AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411&amp;ei=WrGXZcTbGIHc1e8P9Y2o8A8&amp;start=10&amp;sa=N" style="transform:scale(1)" jsname="oHxHid" jsaction="qBEZuc" aria-label="Kết quả khác" data-ve-view="" role="button" data-hveid="CAQQBA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qqq4CegQIBBAE">
                                            <hr class="KXbwLb" aria-hidden="true">
                                            <h3 aria-hidden="true">
                                                <div class="GNJvt ipz2Oe">
                                                    <span class="kQdGHd">
                                                        <span class="OTvAmd z1asCe QFl0Ff">
                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                <path d="M16.59 8.59L12 13.17 7.41 8.59 6 10l6 6 6-6z"></path>
                                                            </svg>
                                                        </span>
                                                    </span>
                                                    <span class="RVQdVd">Kết quả khác</span>
                                                </div>
                                            </h3>
                                        </a>
                                        <a jsname="a79Lwf" jsaction="nF6QQd" class="VknLRd" role="button" style="display:none" tabindex="0" aria-live="polite" data-hveid="CAQQBQ" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QvvYCegQIBBAF">
                                            <hr class="KXbwLb" aria-hidden="true">
                                            <h3>
                                                <span class="GNJvt">Thử lại</span>
                                            </h3>
                                        </a>
                                    </div>
                                    <a jsname="EvDH1d" style="display:none" data-hveid="CAQQBg" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_skCegQIBBAG"></a>
                                </div>
                                <script nonce="x9iHkhRHZETt-9nytNuh5g">
                                    (function() {
                                        var showOptIn = false;
                                        var a = document.getElementsByClassName("o8xTWc")
                                          , b = document.getElementsByClassName("wxIowe");
                                        showOptIn ? (0 < a.length && a[0].classList.add("kur4we"),
                                        0 < b.length && b[0].classList.remove("kur4we")) : (0 < a.length && a[0].classList.remove("kur4we"),
                                        0 < b.length && b[0].classList.add("kur4we"));
                                    }
                                    )();
                                </script>
                                <div>
                                    <div class="fp-nh save-components-async yp" data-api="AIzaSyBs-GJEDqBAn0NiEv03nkWgCUTr2vlaVl0" data-jiis="up" data-async-type="svcps" id="gws-plugins-collections-tray__save-components-async" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QnbUCKAF6BAgEEAc"></div>
                                </div>
                            </div>
                        </div>
                        <div data-hveid="CAcQBQ" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qh6kJegQIBxAF"></div>
                        <div jscontroller="GU4Gab" style="display:none" data-pcs="2" jsaction="rcuQ6b:npT2md"></div>
                        <div role="navigation">
                            <span id="xjs"></span>
                            <div id="gfn"></div>
                            <span id="fvf"></span>
                        </div>
                    </div>
                </div>
                <style>
                    .Tg0csd {
                        bottom: 0;
                        left: 0;
                        position: fixed;
                        right: 0;
                        z-index: 312
                    }
                </style>
                <div class="Tg0csd">
                    <div jscontroller="tboZfc" jsdata="C4mkuf;_;Bmu0rU" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QuqMJegQIBRAA"></div>
                </div>
                <div class="Tg0csd">
                    <div jscontroller="vrkJ0e" data-jiis="up" data-async-type="asyncContextualTask" jsdata="I1xsof;_;Bmu0rY" id="rNi7Zc" class="yp" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4dMLegQICBAA"></div>
                </div>
                <div jscontroller="T5VV" data-essb="1" data-ssc="0" jsaction="rcuQ6b:npT2md"></div>
                <div jscontroller="aDVF7" data-lel="U" jsaction="rcuQ6b:npT2md"></div>
                <div jscontroller="rhYw1b" data-dmd="" data-dvt="d" jsaction="rcuQ6b:npT2md"></div>
                <style>
                    @-webkit-keyframes allow-alert {
                        from {
                            opacity: 1
                        }

                        to {
                            opacity: .35
                        }
                    }

                    .TCIIWe {
                        padding-top: 12px;
                    }

                    @media (min-height: 576px) {
                        .uSolm .qk7LXc {
                            height:100%
                        }

                        .uSolm {
                            padding: 64px 0px
                        }
                    }

                    @media (max-height: 575px) {
                        .uSolm .qk7LXc {
                            height:100%;
                            max-height: 448px
                        }
                    }

                    @media (min-height: 496px) {
                        .GeOznc .qk7LXc {
                            height:100%
                        }

                        .GeOznc {
                            padding: 24px 0px
                        }
                    }

                    @media (max-height: 495px) {
                        .GeOznc .qk7LXc {
                            height:100%;
                            max-height: 448px
                        }
                    }

                    .kJFf0c.ivkdbf {
                        -webkit-filter: none;
                        filter: none
                    }

                    .KUf18.ivkdbf {
                        background-color: rgba(0,0,0,0.6);
                        opacity: 1;
                        visibility: inherit
                    }

                    .VfsLpf.ivkdbf {
                        background-color: #000;
                        opacity: .4;
                        visibility: inherit
                    }

                    .J3Hnlf.ivkdbf {
                        background-color: #202124;
                        opacity: .7;
                        visibility: inherit
                    }

                    .X46m8.ivkdbf {
                        background-color: #000;
                        opacity: .8;
                        visibility: inherit
                    }

                    .cBoDed.ivkdbf {
                        background-color: #303134;
                        opacity: .85;
                        visibility: inherit
                    }

                    .kyk7qb.ivkdbf {
                        background-color: #202124;
                        opacity: .6;
                        visibility: inherit
                    }

                    .qk7LXc.ivkdbf {
                        opacity: 1
                    }

                    .mcPPZ.ivkdbf {
                        opacity: 1;
                        visibility: inherit
                    }

                    .mcPPZ.nP0TDe {
                        cursor: pointer
                    }

                    .mcPPZ.nP0TDe .qk7LXc {
                        cursor: default
                    }

                    .kJFf0c {
                        position: fixed;
                        z-index: 9997;
                        right: 0;
                        bottom: -200px;
                        top: 0;
                        left: 0;
                        -webkit-transition: opacity .25s;
                        transition: opacity .25s;
                        opacity: 0;
                        visibility: hidden
                    }

                    .qk7LXc {
                        display: inline-block;
                        z-index: 9997;
                        background-color: #202124;
                        opacity: 0;
                        white-space: normal;
                        overflow: hidden
                    }

                    .qk7LXc {
                        border-radius: 8px
                    }

                    .qk7LXc {
                        box-shadow: 0px 5px 26px 0px rgba(0,0,0,0.5),0px 20px 28px 0px rgba(0,0,0,0.5)
                    }

                    .qk7LXc.DJEOfc {
                        background-color: transparent
                    }

                    .qk7LXc.DJEOfc {
                        box-shadow: none
                    }

                    .qk7LXc.Fb1AKc {
                        position: relative;
                        vertical-align: middle
                    }

                    .qk7LXc.ulWzbd {
                        position: absolute
                    }

                    .qk7LXc.P1WYLb {
                        border: 1px solid #3c4043;
                        box-shadow: #dadce0
                    }

                    .mcPPZ {
                        position: fixed;
                        right: 0;
                        bottom: 0;
                        top: 0;
                        left: 0;
                        z-index: 9997;
                        vertical-align: middle;
                        visibility: hidden;
                        white-space: nowrap;
                        max-height: 100%;
                        max-width: 100%;
                        overflow-x: hidden;
                        overflow-y: auto
                    }

                    .mcPPZ.xg7rAe {
                        text-align: center
                    }

                    .mcPPZ::after {
                        content: "";
                        display: inline-block;
                        height: 100%;
                        vertical-align: middle
                    }

                    .mcPPZ {
                        tap-highlight-color: rgba(0,0,0,0)
                    }

                    .LjfRsf {
                        height: 0;
                        opacity: 0;
                        position: absolute;
                        width: 0
                    }

                    .VH47ed {
                        visibility: hidden
                    }

                    .TaoyYc {
                        overflow: hidden
                    }

                    .qk7LXc.aJPx6e {
                        overflow: visible
                    }

                    .vAJJzd {
                        opacity: .999
                    }

                    .yMNJR .qk7LXc {
                        max-width: 100%
                    }

                    .cJFqsd .qk7LXc {
                        height: 100%
                    }

                    .rfx2Y .qk7LXc {
                        width: 100%
                    }

                    .BhUHze .qk7LXc {
                        width: 75%
                    }

                    .dgVGnc .qk7LXc {
                        width: 90%
                    }

                    sentinel {
                    }

                    .hObAcc {
                        margin-left: 4px;
                        margin-right: 4px
                    }

                    sentinel {
                    }

                    .gTewb {
                        padding-left: 8px;
                        padding-right: 8px
                    }

                    sentinel {
                    }
                </style>
                <div id="bfoot">
                    <span style="display:none">
                        <span jscontroller="DhPYme" style="display:none" data-atsd="5" data-mmcnt="100" jsaction="rcuQ6b:npT2md"></span>
                    </span>
                </div>
                <div class="spch" style="display:none" id="spch"></div>
                <div jscontroller="YFicMc" style="display:none" jsaction="L6fTBf:SMCzH" id="sfooter" role="contentinfo" data-hveid="CAIQAA" data-ved="2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qpyp6BAgCEAA">
                    <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Đường liên kết ở chân trang</h1>
                    <div id="footcnt">
                        <div class="TCIIWe" style="height:106px" id="fbarcnt">
                            <div class="f6F9Be TrMVnc" id="fbar"></div>
                        </div>
                    </div>
                </div>
                <script nonce="x9iHkhRHZETt-9nytNuh5g">
                    (function() {
                        (function() {
                            var a = Date.now();
                            google.tick("load", "prt", a);
                            google.c.e("load", "imn", String(document.getElementsByTagName("img").length));
                            google.c.ub();
                            google.c.maft(a, null);
                            google.c.miml(a);
                            google.rll(window, !1, function() {
                                google.tick("load", "old")
                            })
                        }
                        )();
                    }
                    ).call(this);
                    (function() {
                        window.google = window.google || {};
                        window.google.ishk = [];
                        function a() {
                            return window.scrollY + window.document.documentElement.clientHeight >= Math.max(document.body.scrollHeight, document.body.offsetHeight)
                        }
                        function b() {
                            a() && 0 === window.google.ishk.length && (window.google.bs = !0,
                            window.removeEventListener("scroll", b))
                        }
                        a() ? window.google.bs = !0 : (window.google.bs = !1,
                        window.addEventListener("scroll", b));
                    }
                    ).call(this);
                </script>
            </div>
        </div>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                for (var i in google.iir || {}) {
                    _setImagesSrc([i], google.iir[i]);
                }
                google.iir = {};
            }
            )();
            (function() {
                google.xjs = {
                    ck: 'xjs.s.OZxnikXpDHs.L.W.O',
                    combam: 'ACAAACoQAAAAAAAAAAAAAABAAAAAAAAEISAcMtkUB_DLIABAABgAAAGqikKAQwCBgM9_QgAAAAAAAEyAwACQBZAKP0MAAMAEqgDsAAAAACDYD0QBAB4EEAAQAwAAIENDIfiAEFACAgAAAMgDgOcBDAcRHgAAAAAAAAAAAAAEMEEwOCD9URAAAQAAAAAAAAAAAABS0uSlQAIAag',
                    cs: 'ACT90oHxwcZD5YBn3NjMI3DV96SSq5fQaA',
                    cssam: 'ACAAACoQAAAAAAAAAAAAAABAAAAAAAAEACAcMNkUBvDIIAAAABgAAAAgAAAAAwCAAAAAAAAAAAAAAACAwAAQBJAKP0EAAMAEqgDsAAAAAAAIAEQBAB4EEAAQAgAAIAMBIfiAEAAAAAAAAAABAAAADAAACAAAAAAAAAAAAAAAAAAAAAD8UQAAAAAAAAAAAAAAAABAAAAEQAIAag',
                    cssopt: false,
                    csss: 'ACT90oG7jod-Jd8TRn7goRzlpdGD_yCDlQ',
                    excm: ['NsEUGe', 'y25qZb', 'AD6AIb', 'fNMhz', 'bXyZdf', 'ZrXR8b', 'du3Q4e', 'ABxRVc', 'rL2AR', 'yChgtb', 'qngJBf', 'cKV22c', 'YuNOCb', 'JxE93', 'ST8mye', 'VZLyBe', 'U3Ovcc', 'TO0csb', 'Oa7Qpb', 'zs9f9d', 'tzTB5', 'XHo6qe', 'FmnE6b', 'jkRPje', 'PoJj8d', 'KzZUob', 'ak946', 'TurKxc', 'PvSBGf', 'Ok4XMd', 'Trirbc', 'eTv59e', 'hfJ9hb'],
                    sepam: false,
                    sepcss: false
                };
            }
            )();
        </script>
        <!-- cctlcm 5 cctlcm -->
        <div id="_WrGXZcTbGIHc1e8P9Y2o8A8_24"></div>
        <style>
            .RTZ84b {
                color: #9aa0a6;
                cursor: pointer;
                padding-right: 8px
            }

            .c2xzTb .RTZ84b {
                padding-top: 1px;
                padding-right: 4px
            }

            .XEKxtf {
                color: #9aa0a6;
                float: right;
                font-size: 12px;
                line-height: 16px;
                padding-bottom: 4px
            }

            .CvDJxb.minidiv {
                margin-top: 0
            }

            #gb {
                min-width: unset;
                position: relative
            }

            .minidiv #gb {
                top: 2px
            }

            #gba {
                display: none
            }

            .Q3DXx #gb>div {
                padding-left: 0
            }

            .minidiv .RNNXgb {
                min-height: 32px;
                border-radius: 16px;
                background: #303134;
                margin: 10px 0 0;
                border: 1px solid #5f6368;
                box-shadow: none;
                border: 1px solid #5f6368
            }

            .emcav.emcat .RNNXgb {
                border-bottom-left-radius: 24px;
                border-bottom-right-radius: 24px
            }

            .minidiv .emcav.emcat .RNNXgb {
                border-bottom-left-radius: 16px;
                border-bottom-right-radius: 16px
            }

            .minidiv .SDkEP {
                padding-top: 0
            }

            .FgNLaf {
                display: none
            }

            .minidiv .logo {
                padding: 0 32px
            }

            .emcav.A8SBwf.h3L8Ub {
                z-index: 989
            }

            .minidiv .iblpc {
                margin-top: 0;
                height: 32px
            }

            .CKb9sd {
                background: none;
                display: flex;
                flex: 0 0 auto
            }

            .minidiv .jfN4p {
                height: 28px;
                width: 86px
            }

            .sbfc textarea.gLFyf {
                white-space: pre-line;
                overflow-y: auto
            }

            .minidiv .gLFyf {
                padding: 0;
                line-height: 22px;
                margin-bottom: 0
            }

            .minidiv .a4bIc {
                margin-top: 5px
            }

            .gLFyf.CJxXMe {
                margin-top: 0
            }

            .VZUv6d {
                font-size: 11px;
                font-weight: bold;
                white-space: nowrap;
                color: #fff;
                line-height: 29px;
                padding: 0 10px
            }

            .minidiv .dRYYxd {
                margin-top: 0;
                height: 32px
            }

            .minidiv .vOY7J {
                line-height: 32px
            }

            .minidiv .ExCKkf {
                width: 20px
            }

            .minidiv .XDyW0e {
                line-height: 32px
            }

            .minidiv .goxjub {
                width: 20px;
                height: 20px
            }

            .minidiv .nDcEnd {
                line-height: 32px
            }

            .minidiv .Gdd5U {
                width: 20px;
                height: 20px
            }

            .minidiv .Tg7LZd {
                height: 32px;
                line-height: 32px
            }

            .minidiv .Tg7LZd .zgAlFc {
                height: 20px;
                width: 20px
            }

            .minidiv .Tg7LZd svg {
                height: 20px;
                width: 20px
            }

            .minidiv .aajZCb {
                box-shadow: 0 4px 6px 0 #171717;
                border-bottom-left-radius: 16px;
                border-bottom-right-radius: 16px
            }

            .h3L8Ub .rLrQHf {
                padding-bottom: 16px
            }

            .h3L8Ub .rLrQHf {
                min-width: 47%;
                width: 47%;
                margin: 8px 16px 0
            }

            .S3nFnd {
                display: flex
            }

            .lh87ke:link,.lh87ke:visited {
                color: #8ab4f8;
                cursor: pointer;
                font: 11px arial,sans-serif;
                padding: 0 5px;
                text-decoration: none;
                flex: auto;
                align-self: flex-end;
                margin: 0 16px 5px 0
            }

            .lh87ke:hover {
                text-decoration: underline
            }

            .sb27 {
                background: url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 -21px;
                background-size: 20px;
                min-height: 20px;
                min-width: 20px;
                height: 20px;
                width: 20px
            }

            .sb43 {
                background: url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 0;
                background-size: 20px;
                min-height: 20px;
                min-width: 20px;
                height: 20px;
                width: 20px
            }

            .sb53.sb53 {
                padding: 0 4px;
                margin: 0
            }

            .sb33 {
                background: url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 -42px;
                background-size: 20px;
                height: 20px;
                width: 20px;
            }

            .Ye4jfc {
                flex-direction: row;
                flex-wrap: wrap
            }

            .sbic.vYOkbe {
                background: center/contain no-repeat;
                border-radius: 4px;
                min-height: 32px;
                min-width: 32px;
                margin: 4px 7px 4px -5px;
            }

            .sbre .wM6W7d {
                line-height: 18px
            }

            .minidiv .wM6W7d {
                font-size: 14px
            }

            .WggQGd {
                color: #c58af9
            }

            .h3L8Ub .yMAEcf {
                border-radius: 100px;
                box-sizing: border-box;
                display: flex;
                min-height: 40px;
                margin: 4px 0 4px 16px;
                width: 396px
            }

            .h3L8Ub .yMAEcf .gmlSVb {
                bottom: 0;
                right: 0
            }

            @media (forced-colors:none) {
                .h3L8Ub .yMAEcf {
                    background: #303134
                }
            }

            .h3L8Ub .yMAEcf {
                width: fit-content
            }

            .minidiv .h3L8Ub .yMAEcf .wM6W7d {
                font-size: 16px
            }

            .h3L8Ub .yMAEcf {
                border: 1px solid #5f6368
            }

            @media (forced-colors:none) {
                .h3L8Ub .yMAEcf.sbhl {
                    background: #3c4043
                }
            }

            .sbhl {
                border-radius: 4px;
                background: #3c4043;
            }

            .UUbT9.i1eWpb .PZPZlf.sbhl {
                background: none
            }

            @media (forced-colors:active) {
                .sbhl {
                    background-color: highlight
                }
            }

            .mus_pc {
                display: block;
                margin: 6px 0
            }

            .mus_il {
                font-family: Arial,Helvetica Neue Light,Helvetica Neue,Helvetica;
                padding-top: 7px;
                position: relative
            }

            .mus_il:first-child {
                padding-top: 0
            }

            .mus_il_at {
                margin-left: 10px
            }

            .mus_il_st {
                right: 52px;
                position: absolute
            }

            .mus_il_i {
                align: left;
                margin-right: 10px
            }

            .mus_it3 {
                margin-bottom: 3px;
                max-height: 24px;
                vertical-align: bottom
            }

            .mus_it5 {
                height: 24px;
                width: 24px;
                vertical-align: bottom;
                margin-left: 10px;
                margin-right: 10px;
                transform: rotate(90deg)
            }

            .mus_tt3 {
                color: #9aa0a6;
                font-size: 12px;
                vertical-align: top
            }

            .mus_tt5 {
                color: #f28b82;
                font-size: 14px
            }

            .mus_tt6 {
                color: #81c995;
                font-size: 14px
            }

            .mus_tt8 {
                font-size: 16px;
                font-family: Arial,sans-serif
            }

            .mus_tt17 {
                color: #e8eaed;
                font-size: 20px
            }

            .mus_tt18 {
                color: #e8eaed;
                font-size: 28px
            }

            .mus_tt19 {
                color: #9aa0a6;
                font-size: 12px
            }

            .mus_tt20 {
                color: #9aa0a6;
                font-size: 14px
            }

            .mus_tt23 {
                color: #9aa0a6;
                font-size: 18px
            }

            .DJbVFb .TfeWfb {
                display: flex;
                flex-wrap: wrap;
                overflow-x: hidden;
                width: 100%;
                height: 52px
            }

            .DJbVFb .AQZ9Vd {
                display: none
            }

            .DJbVFb .xAmryf {
                border-radius: 100px;
                background-color: #303134
            }

            .DJbVFb .TfeWfb {
                display: inherit
            }

            .DJbVFb .xAmryf .eL7oAc {
                display: none
            }

            .DJbVFb {
                background: #3c4043;
                border-radius: 20px
            }

            .DJbVFb:hover {
                background: rgba(95,99,104,0.6)
            }

            .DJbVFb .vYOkbe {
                height: 200px;
                width: 200px;
                flex-shrink: 0;
                margin: 20px 0 20px 8px;
                float: right;
                border-radius: 16px;
                background-color: #fff
            }

            .DJbVFb.sbhl {
                background: rgba(95,99,104,0.6)
            }

            .DJbVFb .ClJ9Yb {
                display: none
            }

            .DJbVFb .wM6W7d {
                flex: initial
            }

            .DJbVFb .wM6W7d span {
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                -webkit-line-clamp: 2;
                overflow: hidden
            }

            .DJbVFb .eIPGRd {
                display: flex;
                flex-direction: row-reverse;
                align-items: stretch;
                margin: 0 20px 0 14px
            }

            .DJbVFb.ytLedb .vYOkbe {
                background-color: #3c4043
            }

            .DJbVFb .kzCE2 {
                font-size: 16px
            }

            .DJbVFb .pcTkSc {
                margin: 20px 6px;
                padding: 0
            }

            .DJbVFb .vYOkbe {
                margin: 20px 0 20px 18px;
                background-color: #fff;
                border-radius: 20px
            }

            .DJbVFb .EOLKOc {
                width: calc(50% - 1px)
            }

            .DJbVFb .EOLKOc:first-child {
                border-bottom-left-radius: 20px
            }

            .DJbVFb .EOLKOc:last-child {
                border-bottom-right-radius: 20px
            }

            .DJbVFb .AZNDm {
                border-top-right-radius: 20px;
                border-top-left-radius: 20px
            }

            .DJbVFb .a5RLac.kzCE2 span {
                -webkit-line-clamp: 3
            }

            .DJbVFb .lnnVSe {
                margin-bottom: auto
            }

            .DJbVFb .a5RLac span {
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                -webkit-line-clamp: 2;
                overflow: hidden;
                margin-right: 10px
            }

            .xAmryf .eL7oAc {
                fill: #bdc1c6;
                padding-top: 1px
            }

            .xAmryf.LvqzR {
                background-color: #394457;
                cursor: pointer;
                color: #8ab4f8
            }

            .xAmryf.LvqzR .eL7oAc {
                fill: #8ab4f8
            }

            .Hulzgf {
            }

            .uhebGb {
                font-style: italic
            }

            .sOmPcf .ZFiwCf {
                background-color: #3c4043
            }

            .U48fD.df13ud {
                margin-top: 16px
            }

            .U48fD.TOQyFc {
                margin-top: 0
            }

            .U48fD.p8FEIf {
                padding-bottom: 0
            }

            .U48fD.ke7M4 {
                padding-left: 0;
                padding-right: 0
            }

            .jRKCUd::before {
                bottom: 12px;
                content: '';
                left: 16px;
                position: absolute;
                right: 16px;
                top: -4px
            }

            a.jRKCUd:hover {
                text-decoration: none
            }

            .TQc1id .ZFiwCf {
                max-width: unset
            }

            .nCFUpc .ZFiwCf {
                width: 100%
            }

            .TQc1id .Bi9oQd {
                display: none
            }

            .kC8B4e .Bi9oQd {
                display: none
            }

            .JCHpcb:hover,.LvqzR .JCHpcb {
                color: #8ab4f8;
                text-decoration: underline
            }

            .JCHpcb {
                color: #aaadb2;
                font: 13px arial,sans-serif;
                cursor: pointer;
                align-self: center
            }

            .DJbVFb,.o6OF0 {
                background: #414143;
                border-radius: 20px
            }

            .o6OF0:hover,.o6OF0.LvqzR {
                background: #515254
            }

            .o6OF0 .eIPGRd {
                display: block
            }

            @media (forced-colors:none) {
                .o6OF0.sbhl {
                    background: #515254
                }
            }

            @media (forced-colors:active) {
                .o6OF0.sbhl {
                    background-color: highlight
                }
            }

            .o6OF0 .AQZ9Vd {
                display: none
            }

            .o6OF0 .sbic {
                display: none
            }

            .o6OF0 .pcTkSc {
                display: none
            }

            .o6OF0 .wM6W7d {
                display: none
            }

            .o6OF0 .eIPGRd {
                max-width: 100%;
                margin: 0
            }

            .az9Ajc {
                padding_top: 0px
            }

            .o6OF0 .SHFPkb.ZJ594e {
                padding-right: 58px
            }

            .z76Rnb.LvqzR {
                color: #e8eaed;
                background-color: #3c4043
            }

            .XAFD5c.iNF0Vd {
                background-size: 136px
            }

            .o6OF0 .TfeWfb {
                display: flex;
                gap: 6px;
                height: 42px;
                flex-wrap: wrap;
                overflow: hidden;
                padding: 0;
                margin-top: 16px
            }

            .xAmryf.LvqzR {
                color: #e8eaed;
                background-color: #3c4043
            }

            .rnAixd {
                color: #f28b82
            }

            .izxCJf {
                color: #81c995
            }

            .s2Wjec {
                display: block
            }

            .Q82Okf {
                font-size: 16px;
                font-family: Arial,sans-serif
            }

            .IDVnvc.sbhl {
                border-radius: 16px
            }

            .cRV9hb .pcTkSc .ClJ9Yb.ENMKxf span {
                -webkit-line-clamp: 1
            }

            .aVbWac .sbic.vYOkbe {
                height: 90px;
                width: 90px;
                border-radius: 12px;
                margin: 0
            }

            .fLciMb {
                border-radius: 50%;
                color: #e8eaed;
                cursor: pointer;
                height: 24px;
                margin-top: 4px;
                padding: 8px;
                width: 24px
            }

            .minidiv .fLciMb {
                margin-top: 6px
            }

            .fLciMb:hover {
                background-color: #3c4043;
                text-decoration: none
            }

            .ZOyvub {
                visibility: hidden;
                position: absolute;
                top: 50px;
                padding: 5px 6px;
                background-color: #424548;
                color: #f8f9fa;
                border-radius: 4px;
                font-size: 12px;
                letter-spacing: 1px;
                left: 50%;
                transform: translateX(-50%);
                width: max-content
            }

            #gb {
                height: 0;
                padding-left: 16px;
                padding-right: 16px
            }

            .hdtb-ab-o .LHJvCe {
                opacity: 0;
                top: 13px
            }

            .SknMB,.SknMB:visited {
                align-items: center;
                color: #8ab4f8;
                display: flex;
                height: 40px
            }

            .ZI7elf {
                cursor: pointer;
                color: #e8eaed;
                font-size: 16px;
            }

            .q0yked {
                color: #bdc1c6;
            }

            .q0yked:hover {
                background-color: #303134
            }

            .q0yked a {
                align-items: center;
                display: flex;
                text-decoration: none;
                padding: 18px 24px;
                flex: 1;
                gap: 16px;
            }

            .uXoAyd {
                display: flex;
                flex-direction: column;
                gap: 4px
            }

            .CbAZb {
                background: #202124;
                border-bottom: 1px solid #3c4043;
                bottom: 0;
                overflow-y: auto;
                position: fixed;
                right: -360px;
                top: 0;
                width: 360px;
                font-family: Google Sans,arial,sans-serif;
                display: flex;
                flex-direction: column
            }

            .AeB7Sc {
                background: rgba(0,0,0,0.6);
                bottom: 0;
                display: none;
                left: 0;
                overflow: hidden;
                position: fixed;
                right: 0;
                top: 0;
                z-index: 9000
            }

            .S8wJ3 {
                color: #e8eaed;
                font-family: Google Sans,arial,sans-serif;
                flex: 1;
                font-size: 22px;
            }

            .tGS0Nc {
                display: flex;
                gap: 12px;
                align-items: center;
                margin: 18px 24px;
                color: #e8eaed
            }

            a:visited.tGS0Nc {
                color: #e8eaed
            }

            .tGS0Nc .z1asCe {
                color: #a6c9fc
            }

            .fgc1P {
                border-top: 1px solid #3c4043
            }

            .bepeF {
                color: #9aa0a6;
                cursor: pointer;
                padding: 8px;
            }

            .kQEH5b {
                font-size: 12px;
                color: #bdc1c6;
            }

            .cQ2awd {
                display: flex;
                align-items: center;
                height: 70px;
            }

            .bsfygf {
                padding: 20px
            }

            .S4xgid {
                cursor: pointer;
                display: flex;
                gap: 16px;
                padding: 18px 24px;
            }

            .UCGAnb {
                flex: 1
            }

            .LZTko:hover {
                background: #303134;
                box-shadow: -56px 0 #303134,24px 0 #303134,-56px -10px 0 #303134,24px -10px 0 #303134;
                cursor: pointer
            }

            .q0yked .z1asCe {
                color: #bdc1c6
            }

            .UCAEse {
                height: 30px;
                margin-bottom: 5px;
                margin-top: -5px
            }

            .ogD9ue {
                align-items: center;
                display: flex
            }

            .rhJQGd {
                color: #9aa0a6;
                margin-right: 6px
            }

            .W3aG6d {
                align-items: center;
                display: flex;
                min-height: 48px;
                flex-shrink: 0;
                padding-left: 40px;
            }

            .aoMqnc {
                animation: loading-pulse 1.25s ease-out 0s infinite alternate;
                background: #303134;
                border-radius: 4px;
                height: 24px;
                margin: 0 24px;
                opacity: 0.2;
                width: 100%
            }

            .aztjNb {
                color: #e8eaed;
                font-size: 11px;
                font-weight: 700;
                letter-spacing: 0.3px;
                line-height: 16px;
                text-transform: uppercase
            }

            .dVmoif {
                display: flex
            }

            .RVVZab {
                background-color: #8ab4f8;
                border-radius: 4px;
                color: #202124;
                height: 14px;
                margin-right: 8px;
                padding: 4px
            }

            .kzt0Nc {
                margin-top: auto;
                padding: 24px;
                font-size: 12px
            }

            .kzt0Nc a {
                color: #9aa0a6
            }

            .kzt0Nc a:visited {
                color: #9aa0a6
            }

            .wIV7Db {
                visibility: hidden
            }

            .mn51Ef {
                margin-left: 5px;
                vertical-align: text-bottom
            }

            .cF4V5c {
                background-color: #202124
            }

            .cF4V5c g-menu-item {
                display: block;
                font-size: 14px;
                line-height: 23px;
                white-space: nowrap
            }

            .cF4V5c g-menu-item a,.cF4V5c .y0fQ9c {
                display: block;
                padding-top: 4px;
                padding-bottom: 4px;
                cursor: pointer
            }

            .cF4V5c g-menu-item a,.cF4V5c g-menu-item a:visited,.cF4V5c g-menu-item a:hover {
                text-decoration: inherit;
                color: inherit
            }

            .zriOQb g-menu-item {
                color: #969ba1
            }

            .zriOQb g-menu-item a,.zriOQb .y0fQ9c {
                line-height: 16px;
                padding-top: 8px;
                padding-bottom: 8px
            }

            .hdtb-tl-sel {
                border: 1px solid #5f6368;
                box-shadow: inset 0 1px 2px 0 rgba(23,23,23,0.9);
                background: #303134;
                color: #e8eaed;
            }

            .cdtWk {
                display: inline-block;
                line-height: 29px
            }

            .Doo7xc {
                line-height: 40px;
                width: 120px
            }

            .RVRNTb div[role="none"] {
                line-height: 36px;
                padding: 0
            }

            .RVRNTb .z4R3Z {
                padding-right: 26px;
                text-align: left;
                color: #bdc1c6
            }

            .RVRNTb .z4R3Z.yb2zA {
                color: #8ab4f8
            }

            .RVRNTb a.kQyaVc,.RVRNTb a.kQyaVc:visited {
                padding: 0;
                color: #bdc1c6
            }

            .RVRNTb a.kQyaVc:hover {
                text-decoration: none;
                color: #bdc1c6
            }

            .BslMec {
                cursor: pointer;
                color: #9aa0a6;
                font-size: 12px;
                display: block
            }

            .BpGBNe {
                vertical-align: top
            }

            .ijreF {
                display: inline-block;
                vertical-align: top
            }

            .RVceMc {
                float: right
            }

            .ebsfL {
                white-space: nowrap
            }

            .GP4Iec .BpGBNe {
                float: right
            }

            .GP4Iec .S7TGef {
                max-width: calc(100% - 26px)
            }

            .L3FBEc {
                width: 26px;
                display: inline-block
            }

            .wWjvRd {
                vertical-align: text-bottom;
                padding: 0 5px
            }

            .muaC1e {
                overflow-x: scroll;
                -ms-overflow-style: none;
                scrollbar-width: none
            }

            .muaC1e::-webkit-scrollbar {
                display: none
            }

            .Lj8KXd .QBbvme {
                margin-top: 44px
            }

            .yyoM4d {
                padding-top: 3px;
                padding-bottom: 7px;
                top: 57px
            }

            .hdtb-mn-hd {
                color: #9aa0a6;
                display: inline-block;
                position: relative;
                padding-top: 0;
                padding-bottom: 0;
                padding-right: 18px;
                padding-left: 12px;
                line-height: 22px;
                cursor: pointer
            }

            .hdtb-mn-hd:hover {
                color: #ddd
            }

            .hdtb-mn-hd:hover .gTl8xb {
                border-color: #ddd transparent
            }

            .hdtb-mn-hd:active {
                color: #8ab4f8
            }

            .hdtb-mn-hd:active .gTl8xb {
                border-color: #8ab4f8 transparent
            }

            .LkcePc {
                display: inline-block;
                width: var(--center-abs-margin);
            }

            .nvELY {
                background-position: left center;
                background-repeat: no-repeat;
                background-image: url(//ssl.gstatic.com/ui/v1/menu/checkmark2-light.png);
            }

            .Tlae9d a,.Tlae9d div.y0fQ9c {
                padding-left: 32px;
                padding-right: 32px
            }

            .KTBKoe {
                display: inline-block;
                padding-right: 6px;
                white-space: nowrap
            }

            .hdtb-mn-hd.Yg3U7e {
                padding-left: 0
            }

            .gTl8xb {
                border-color: #9aa0a6 transparent;
                border-style: solid;
                border-width: 5px 4px 0 4px;
                width: 0;
                height: 0;
                margin-left: -2px;
                top: 50%;
                margin-top: -2px;
                position: absolute
            }

            .T3kYXe,.OouJcb,.rzG2be {
                color: #bdc1c6
            }

            .OouJcb,.rzG2be {
                background-color: #202124;
                border: 1px solid #5f6368;
                border-radius: 1px;
                font-size: 13px;
                height: 17px;
                left: 50px;
                line-height: 17px;
                margin: 0 4px;
                padding: 5px;
                position: absolute;
                width: 84px
            }

            .OouJcb:focus,.rzG2be:focus {
                border: 1px solid #4487f6;
                box-shadow: inset 0 1px 2px rgba(0,0,0,.3);
                outline: none
            }

            .J6UZg .goog-date-picker {
                left: 154px;
                background-color: #303134;
                border-radius: 2px;
                border: none;
                font-size: 12px;
                outline: none;
                padding: 5px 1px 10px;
                position: absolute;
                top: 61px;
                -webkit-user-select: none
            }

            .J6UZg .goog-date-picker table {
                padding: 0 10px;
                width: 175px
            }

            .J6UZg .goog-date-picker table thead td {
                border-bottom: 1px solid #3c4043
            }

            .J6UZg .goog-date-picker tbody th {
                width: 0
            }

            .J6UZg tr.goog-date-picker-head {
                height: 27px
            }

            .J6UZg tr.goog-date-picker-head td {
                white-space: nowrap
            }

            .J6UZg .goog-date-picker-monthyear {
                font-size: 13px
            }

            .J6UZg .goog-date-picker tbody {
                outline: none;
                font-size: 13px
            }

            .J6UZg .goog-date-picker td,.J6UZg .goog-date-picker th {
                text-align: center
            }

            .J6UZg .goog-date-picker-btn {
                background: none;
                border: none;
                cursor: pointer;
                font-size: 12px;
                outline: none;
                padding: 0;
                position: relative;
                top: -1px
            }

            .J6UZg .goog-date-picker-btn:not(.suap3e) {
                color: #bdc1c6
            }

            .J6UZg button.goog-date-picker-btn {
                font-size: 12px;
                vertical-align: middle
            }

            .J6UZg .goog-date-picker-wday,.J6UZg .goog-date-picker-date {
                font-weight: normal;
                padding: 0 1px
            }

            .J6UZg .goog-date-picker-wday {
                padding-top: 3px;
                line-height: 15px
            }

            .J6UZg td.goog-date-picker-selected {
                background-color: #8ab4f8;
                border-radius: 2px;
                color: #202124
            }

            .J6UZg .goog-date-picker-other-month {
                color: #212327
            }

            .J6UZg .goog-date-picker-date {
                cursor: pointer;
                width: 20px;
                line-height: 15px
            }

            .J6UZg .goog-date-picker-foot {
                display: none
            }

            .J6UZg td.goog-date-picker-date:hover {
                background-color: #212327;
                border-radius: 2px
            }

            .J6UZg td.goog-date-picker-year,.J6UZg td.goog-date-picker-month {
                padding: 3px 0
            }

            .J6UZg button.goog-date-picker-year,.J6UZg button.goog-date-picker-month {
                color: #fff
            }

            .J6UZg button.goog-date-picker-month {
                width: 77px
            }

            .J6UZg button.goog-date-picker-year {
                width: 50px
            }

            .J6UZg .goog-date-picker-menu {
                background: #202124;
                border: solid 1px #4487f6;
                cursor: pointer;
                outline: none;
                position: absolute
            }

            .UfY8P tr:nth-child(2) .goog-date-picker-other-month {
                color: #9aa0a6
            }

            .T3kYXe {
                padding: 0 15px
            }

            .suap3e {
                color: #212327;
                pointer-events: none
            }

            .vOvh1b {
                left: 0;
                background: #202124;
                height: 100%;
                -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=75)";
                opacity: .75;
                position: fixed;
                top: 0;
                width: 100%;
                z-index: 1000
            }

            .J6UZg {
                left: 50%;
                background: #202124;
                border: 1px solid #3c4043;
                box-shadow: 0 4px 16px rgba(0,0,0,0.8);
                height: 241px;
                margin-left: -202px;
                position: fixed;
                top: 250px;
                width: 373px;
                z-index: 1001
            }

            .QIQ7Cc.J6UZg {
                left: 0;
                margin-left: 0
            }

            .QIQ7Cc .Jy9Ore,.QIQ7Cc .Qtsmnf {
                left: 5px
            }

            .QIQ7Cc .NwEGxd {
                left: -8px
            }

            .Gwgzqd {
                right: 11px;
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAY0lEQVR4AWMYQeD///8C5KtBKOAH4ntA3I9HTT9UDS8hw9r/Q0A/VkMgoB2rZnwa8ImRalg9NleSatg0kG6KDEG4CmEQpYY0gjC6YZQEdju6GDWiv4FgiiUtQVKeRQQZRg4AACRV2JNNVw6ZAAAAAElFTkSuQmCC) center no-repeat;
                cursor: pointer;
                height: 20px;
                position: absolute;
                top: 10px;
                -webkit-user-select: none;
                width: 20px
            }

            .Jy9Ore {
                left: 42px;
                color: #bdc1c6;
                font-size: 16px;
                position: absolute;
                top: 34px
            }

            .Qtsmnf {
                left: 42px;
                color: #bdc1c6;
                position: absolute
            }

            .tmDYm {
                top: 72px
            }

            .iWBKNe {
                top: 111px
            }

            .OouJcb {
                top: 65px
            }

            .rzG2be {
                top: 104px
            }

            .NwEGxd {
                position: relative
            }

            .qomYCd {
                left: 50px;
                background-color: #303134;
                border-bottom-left-radius: 2px;
                border-top-left-radius: 2px;
                height: 37px;
                position: absolute;
                top: 61px;
                -webkit-transition: top .13s linear;
                width: 110px
            }

            .KbfSHd {
                top: 100px
            }

            .lRiKjb {
                -webkit-transition: none
            }

            .Ru1Ao {
                left: 54px;
                position: absolute;
                top: 143px
            }

            .BwGU8e {
                border-radius: 2px;
                border-radius: 2px;
                cursor: pointer;
                display: inline-block;
                font-size: 11px;
                font-weight: bold;
                height: 16px;
                line-height: 16px;
                min-width: 54px;
                padding: 6px 8px 5px;
                text-align: center;
                -webkit-transition: all 0.218s,visibility 0s;
                -webkit-user-select: none
            }

            .BwGU8e[disabled] {
                pointer-events: none;
                background-color: #0b0d0e;
                border-color: #0b0d0e;
                color: #9aa0a6
            }

            .fE5Rge {
                color: #202124;
                background-color: #bdc1c6;
                border: 1px solid #3c4043
            }

            .fE5Rge:hover {
                background-color: #171717;
                border: 1px solid #050607
            }

            .fE5Rge:focus {
                background-color: #394457;
                border: 1px solid #08101e
            }

            .CBvvz {
                margin: -8px 0px 0px;
                margin: -30px 0px 0px;
            }

            .rskU3c .bOiwif {
                animation: ghost-card-shimmering 1.3s infinite;
                background: -webkit-linear-gradient(left,rgba(33,35,39,0) 0%, rgba(33,35,39,.5) 50%, rgba(33,35,39,0) 99%, rgba(33,35,39,0) 100%);
                background: linear-gradient(to right,rgba(33,35,39,0) 0%, rgba(33,35,39,.5) 50%, rgba(33,35,39,0) 99%, rgba(33,35,39,0) 100%);
                bottom: 0;
                right: 0;
                left: 0;
                position: absolute;
                top: 0;
                transform: translate3d(-100%,0,0)
            }

            .rskU3c {
                overflow-x: hidden;
                position: relative;
                width: 100%
            }

            .G8qI4b {
                padding: 0;
            }

            .DYiTxe {
                padding: 0 0 12px;
                border-bottom: 1px solid rgba(255,255,255,.05)
            }

            .N6dG3e,.e4XSEd {
                display: block;
                width: 100%
            }

            .N6dG3e {
                background-color: #394457;
                height: 16px;
                margin-bottom: 8px
            }

            .e4XSEd {
                background-color: rgba(255,255,255,.05);
                height: 12px
            }

            .AMbnUc {
                padding: 12px 0 0;
            }

            .ysLSm {
                background-color: rgba(255,255,255,.05);
                display: block;
                height: 60px;
                width: 100%
            }

            .v5jHUb {
                display: none
            }

            .FcOujd .v5jHUb {
                display: block;
                border: 1px solid #3c4043;
                border-top: 0;
                margin-bottom: 30px
            }

            .ULSxyf {
                margin-bottom: 44px
            }

            .H7QZHe {
                margin: 0 0 8px;
                background-color: #202124
            }

            .hlcw0c {
                margin-bottom: 44px
            }

            .D0ONmb .hlcw0c:last-child {
                margin-bottom: 0
            }

            .FcOujd .ULSxyf:first-child {
                margin-top: 44px
            }

            .A9Y9g {
                flex: 1 1 100%;
                min-width: 0
            }

            .pAEXpf {
                flex: 1 1 auto
            }

            .KAO3Kc {
                display: block;
                height: 100%
            }

            .IajJf {
                flex-shrink: 1
            }

            .myAtwe {
                margin-top: auto
            }

            .cEaSVc {
                margin-right: auto
            }

            .lOdyRd {
                margin-bottom: auto
            }

            .LnCrMe {
                margin-left: auto
            }

            .aBeYNc {
                right: -23px;
                position: absolute;
                top: 0;
                width: 48px;
                height: 48px
            }

            .c2xzTb .LC20lb {
                margin-bottom: 0
            }

            .MMgsKf {
                padding-top: 2px
            }

            .NXKJM {
                display: -webkit-box;
                overflow: hidden;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 1
            }

            .hceuRc {
                -webkit-box-orient: vertical;
                display: -webkit-box;
                -webkit-line-clamp: 2;
                overflow: hidden
            }

            .xvfwl {
                margin-top: 4px
            }

            .TbwUpd.ojE3Fb a.fl {
                padding-top: 0;
                font-size: 12px;
                line-height: 18px;
            }

            .iG7WGe {
                color: #dadce0;
                padding: 0;
                text-align: center;
                width: 16px
            }

            .qncq2c {
                font-size: 12px;
                line-height: 16px;
                margin-left: 6px
            }

            .ob9lvb.HCMUuf {
                color: #9aa0a6
            }

            .csDOgf.I5pXif {
                position: absolute
            }

            .csDOgf.Pyz0Gd {
                margin-top: 2px
            }

            .TNT2l {
                font-style: normal
            }

            .fJOpI.H9lube {
                background-color: #fff;
                border: 1px solid #fff
            }

            .P1UpZb {
                background-color: #fff;
                border: 1px solid #3c4043
            }

            .oqQXff {
                height: 16px
            }

            .UfGzPc {
                border-top: 1px solid #3c4043;
                margin-left: 0
            }

            .YeThId {
                border-top: 1px solid #3c4043
            }

            .FalWJb {
                background: #202124
            }

            .rM2aqb {
                display: none
            }

            .adDDi.PJI6ge {
                padding-bottom: 0
            }

            .DhDny {
                color: #bcc0c3;
                font: 14px/20px Roboto-Medium,HelveticaNeue-Medium,Helvetica Neue,sans-serif-medium,Arial,sans-serif;
                display: inline-block;
                vertical-align: middle
            }

            .EX9eNe {
                color: #868b90;
                margin-left: 4px;
                vertical-align: middle
            }

            .spch-dlg {
                background: transparent;
                border: none
            }

            .spch {
                background: #202124;
                height: 100%;
                left: 0;
                opacity: 0;
                overflow: hidden;
                position: fixed;
                text-align: left;
                top: 0;
                visibility: hidden;
                width: 100%;
                z-index: 10000;
                transition: visibility 0s linear 0.218s,background-color 0.218s;
                background: rgba(0,0,0,.0)
            }

            .s2fp.spch {
                opacity: 1;
                transition-delay: 0s;
                visibility: visible;
                background: rgba(0,0,0,.0)
            }

            .close-button {
                background: none;
                border: none;
                color: #9aa0a6;
                cursor: pointer;
                font-size: 26px;
                right: 0;
                line-height: 15px;
                opacity: .6;
                margin: -1px -1px 0 0;
                padding: 0 0 2px 0;
                height: 48px;
                width: 48px;
                position: absolute;
                top: 0;
                z-index: 10
            }

            .close-button:hover {
                opacity: .8
            }

            .close-button:active {
                opacity: 1
            }

            .spchc {
                display: block;
                height: 42px;
                pointer-events: none;
            }

            .inner-container {
                height: 100%;
                opacity: .1;
                pointer-events: none;
                width: 100%;
                transition: opacity .318s ease-in
            }

            .s2ml .inner-container,.s2ra .inner-container,.s2er .inner-container,.OJaju .inner-container {
                opacity: 1;
                transition: opacity 0s
            }

            .google-logo {
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALwAAABACAQAAAAKENVCAAAJ3klEQVR4Ae1ce5CO1xn/3r0Gi2nVFGmoJEQjg0p2pDo7kWSXiLZCVyQupcUMNhqXdUnC2LRFklLTGhJpMhVTy6pUSFpdNuteCYoYUYJ0xKUUiTsb+/s91c9a7/Pev2+/z3TkPc9fe97zO+85v/N8z3me55x3I2H5Py5sJgPxKspxUE6jEsBZ7McqzGA+v85IPBKKX4NvshA7xbUAWMneki6R2CQUr4dNMQeXJUDBQQ6S1FuXJOwyzXUJIokQl2pm8nlclFjKVra5Rc3CzSOeLbFNYi6oYIEYocbHTTy74bzEWfC6pIXEx0U8f4pKR0p3Yy5HMp+PsSuf5nOyGMcdWpGPhKYmDuLZB7SReRK/5F324UgKc1AMKNoHxDGxkHg+atV2VEiRZHn+EFuhtEa0h8TzdvzHal7Y2n9YYnAoKuKkPSReDKy00F7GuoEHl8N+cU0qJJ59LbSvltvC+DLpXg0zcUjRvk/qh4TfDOKHKtor5f6Q7ptAvBjYo4j/nWoUSrKIZ0dF+0U2vDmbVri5/kYRPzf5OiRZ7CITMBcLr8prHM881omJjDrM4/gq/FyOl1ypHYvx4B0yEDNRguVYIEV8VNJqbmokjQ9yFGajGAsxhyOZLSk+aWGdcef3k6k9YvAh/MmebsZFlAR8c0cswiUHfDEfDPT+7rLGhv43C5nJCF7GjuvCocE1XhrJSzjmkC4fL1nuxH9NNT6l1ynB0gpl4lGwgnd70nYn/uKJXy7f9tT0e7HRFbuTd2GRqaIomMZLKsfigmuvh5jndgKlLfyyJBqYgf45fpxnH1fi83HWF3+GPVzxT3u/H0fxj1iJl/oo9RkROcaReBmomk1LFu18XgIWFjrSVhAMDXKoI354MLwf8Zp22RpoRmOdNH60ajLM10pKYAIy4502B9m1NSbSetmMzJMiiSZeUlEaeEY97MRPVg36J4p4kRv2ltm4Yt3O8AofZ+ur0g0zbOm5Cmmn9warFcVxTDfhT9gMVgs16hbWwx0cwVR25r1sI73wFiriIZ6FGoArmM8ubMBMNuMAbFHPPmdjK/GTFPE/SRzx1fFvGj5SgwBetGSCamMqqNpsMW3yhvZDQEzT7iPr4BULCavEuIHH+/r9UqTfz+ZYGyvxbKwXE9v4Hct5xQvq+XyLH8+RivgRiSFeOaZ9tV6wu8vWCYXOr37SRdPG3o74vqDCP+KCr3TafiUDy2IjXi811jk5jnhDmV7TwthpmeHrmwQu1/1qvQHxGddFHaNGsrH6nX9V+HGu+IkK/241fqXCj3RGSxb2BSdeMnDKVHtMvmGjPZ35+Lsa0Wta4x9QD1cmjviqY5R7VP+bPG4ipGCbfY9gQ8CE/8jjBk8adqtf1rV7bk3UL2Gre5zCHwUnnp3VTIdYlrExJ+OIlQ+cY12zO5mlJnbe915YrrtwrHpTVAv4jBpiTz1EL9+Fg6Oa2CuGPWiwgycxQNU95Y6WFBwISjymKEJrmSNzWYwr4lCwnnerK3z4QA2tKyNxS4Fawqhu4w+mukvexyusgyu2rNE0Zd/reb6/gZrolCh+jvKWPHM6mBmY+HfN8fa1OtblcHNbMxd4lW1sdyfxK9WoBJG4pdjUzwdVdetMdZt9e9hhPnyMmrbF6pKJH95kp7EoWlOmDI138qxvYOJ36TQ6W2M2zjmS/jELWM/50mpri7N1Z5yZmHScsmf1za4klvoS956VJpSanUQ/vNnxxN+idaY0AN7xRvPhwMR/ZqorN71V+/UlfEgMj0ur2JwInWcPZbK6O+T23vbtZbmp9XarxqLUF19uW6YdwbPpzAlM/GHxLDjMSWzsf03bElCzWzwJX3xoevGF6xl2bDJvLz60qf0Ga6M1S/VS+Ih9mdfpHr1VJzDx//QgfRV7+F1lvOHIfaygJ9gsZuoHqbfPq+pZ2/0zkupjrC5Y+lDHNLjMTM/Fr6025+lRit4y1XzhnfTmpMDEr3Dk/DRm8p6YPkyQXOtlJhUS+ArbK8qE7at7nqDqH/YckIoxOYq27Cl/6Inv6eB6Pqvqcrzw2BiY+Gk2Pd/GQcHP0cwvnW+lnncE1vZsnNQHEqafb7b1iYeobF+VA9ZM4cs9AjAD6xX+W8p18LXybBtvAIU97OA1Lu8vQurrkDlqcB4LRHs/fcCAy2yhbP+BgDr7Y73w1weMTQr/pCteJz82VN+R00ebea57VFlw4iUdJ9WM3Q1MH6yUpl7ER9jGfsKDBWzucxj3ZyuGz1pajdJ2kG0d+2qv387hNxbWEnhnO+I74IJLjDpYq5O0cjSWk2NMkk1Rve5wDu2kEy6J4CyHaL23vr6TwzF0JYrZWTJsQ81gZxTbg2P8UQxbPHrIQn2+pY3BpzTt+JfcpnIwmvo+Nnx/S5J2p2kbz8BeffGcj1sIysTMmNPCDeW06nWzTa8NDrnBJ0rNz+3rnucSf51HGWZxHIdxOJ/DbKx2/m4E7zksUYTdbQ3XsI80EkMMNmE/rLc+thi5HNDyng3sx8ZV+P7WI2yAHbXe2fAr2JMNormV5hyBA3EdhAyzcTSd2dH5G7xdBmKzNYaVFEW8Fn4XhyTestjF3VNOodk2okKcyku2UU10wV92xE+wzavIEX8RX9bg6M/AEjsMxBe45PiN2Pf8vnNtgGWxcw7iRQ8vORULJGiZ59CPgTlB4ZglhgP+94k/7GYtrA04pi/18Y/7tZ/eOBIT7fulkwPdmvoZgXqa5rJ8hhSBvmhykotjl4KXfbDnsCfm6x218XaAOX0uucE/MM7iaBwNRNVxjtEmxlV+gIOePR1gFy+85GKfJ/4T7wBNnnCfEY6xQ1wXmgwOwxnxKL7upF2YyZ5YiovuPyCsYL9YPmFgLY5wJg97OMy/J2ZyqHOeBLs5RDJ88fU4Eccd8oiv/y9SR4neJ4LenWRDTMUJx1GtZlfvAMp7sjkcizdkDbZj/1XZiXKZJxMkl3Xiuz8p93McFmEzPsFefIiFLJR2MXycbEg7FmLhVeTeKvwYto0Bn84u+DVKsQufYjtKWCCNovUqN8qfxzirdMnFFCzDDuzHHmyQeRzuHgOpP0LBFn3LIUmiiQ9F50aT+1VMRL46ksaeKOMDXlu3cv8yQ42vuTTh5GtnRljnHmuYoxesQySZEsFXQFhg/mIdv3BuJU+IqXB0zZc71PjWgIiZervWszPOqzRvw5D4BAhmiSrYxLzq7KXB+/AmqJ7/FpHQ1CRAJMsedOEUyvEO3sdhhxi2QaKWPHQnW+KEBCqoVHmVmkroTvI+HAlCO/smetHDAKoJyn1oP6q1PdT4REkKB+BTxbU+P0rePzANUwaSym54E/vAaso/wxL+LJn/ryTUeJVzlaZsKU11Kjok/haSkPiQ+FD+CzU7ChgVP+WTAAAAAElFTkSuQmCC) no-repeat center;
                background-size: 94px 32px;
                height: 32px;
                width: 94px;
                top: 8px;
                opacity: 0;
                float: right;
                left: 255px;
                pointer-events: none;
                position: relative;
                transition: opacity .5s ease-in,left .5s ease-in
            }

            .s2fp .google-logo {
                opacity: 0.54;
                left: 270px;
                transition: opacity .5s ease-out,left .5s ease-out
            }

            .inner-container {
                width: 572px
            }

            .spchc {
                background: #202124;
                box-shadow: 0 2px 6px rgba(0,0,0,.2);
                margin: 0;
                min-width: 100%;
                overflow: hidden;
                padding: 51px 0 50px 126px;
                position: absolute
            }

            .spch.s2fp.t2n14d {
                background: rgba(0,0,0,0.9)
            }

            .LgbsSe {
                background-color: #fff;
                border: 1px solid #f8f9fa;
                border-radius: 100%;
                bottom: 0;
                box-shadow: 0 2px 5px rgba(0,0,0,.1);
                cursor: pointer;
                display: inline-block;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                right: 0;
                transition: background-color 0.218s,border 0.218s,box-shadow 0.218s;
                transition-delay: 0;
                position: absolute;
                opacity: 0;
                left: -83px;
                top: -83px;
            }

            .s2fp .LgbsSe {
                opacity: 1;
                pointer-events: auto;
                transform: scale(1);
                left: 0;
                top: 0
            }

            .s2ra .LgbsSe {
                background-color: #ea4335;
                border: 0;
                box-shadow: none
            }

            .r8s4j {
                background-color: #dadce0;
                border-radius: 100%;
                display: inline-block;
                opacity: 1;
                pointer-events: none;
                position: absolute;
                transform: scale(.01);
                transition: opacity 0.218s;
                height: 151px;
                left: -28px;
                top: -28px;
                width: 151px
            }

            .button-container {
                pointer-events: none;
                position: relative;
                transition: transform 0.218s,opacity 0.218s ease-in;
                transform: scale(.1);
                height: 95px;
                right: -31px;
                top: -27px;
                width: 95px;
                float: right
            }

            .s2fp .button-container {
                transform: scale(1)
            }

            .s2ra .LgbsSe:active {
                background-color: #c5221f
            }

            .LgbsSe:active {
                background-color: #f8f9fa
            }

            .microphone {
                height: 87px;
                pointer-events: none;
                position: absolute;
                width: 42px;
                left: 17px;
                top: 7px;
                transform: scale(.53)
            }

            .receiver {
                background-color: #999;
                border-radius: 30px;
                height: 46px;
                left: 25px;
                pointer-events: none;
                position: absolute;
                width: 24px
            }

            .wrapper {
                bottom: 0;
                height: 53px;
                left: 11px;
                overflow: hidden;
                pointer-events: none;
                position: absolute;
                width: 52px
            }

            .stem {
                background-color: #999;
                bottom: 14px;
                height: 14px;
                left: 22px;
                pointer-events: none;
                position: absolute;
                width: 9px;
                z-index: 1
            }

            .shell {
                border: 7px solid #999;
                border-radius: 28px;
                bottom: 27px;
                height: 57px;
                pointer-events: none;
                position: absolute;
                width: 38px;
                z-index: 0;
                left: 0px
            }

            .s2ml .receiver,.s2ml .stem {
                background-color: #f44
            }

            .s2ml .shell {
                border-color: #f44
            }

            .s2ra .receiver,.s2ra .stem {
                background-color: #fff
            }

            .s2ra .shell {
                border-color: #fff
            }

            .text-container {
                pointer-events: none;
                position: relative
            }

            .spcht {
                font-weight: normal;
                line-height: 1.2;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                text-align: left;
                -webkit-font-smoothing: antialiased;
                transition: opacity .1s ease-in,margin-left .5s ease-in,top 0s linear 0.218s;
                font-size: 27px;
                left: 7px;
                top: .2em;
                width: 490px;
                margin-left: 32px
            }

            .s2fp .spcht {
                margin-left: 0;
                opacity: 1;
                transition: opacity .5s ease-out,margin-left .5s ease-out
            }

            .spchta {
                color: #8ab4f8;
                cursor: pointer;
                font-size: 18px;
                font-weight: 500;
                pointer-events: auto;
                text-decoration: underline
            }

            .spch-2l.spcht,.spch-3l.spcht,.spch-4l.spcht {
                transition: top 0.218s ease-out
            }

            .spch-2l.spcht {
                top: -.6em
            }

            .spch-3l.spcht {
                top: -1.3em
            }

            .spch-4l.spcht {
                top: -1.7em
            }

            .s2fp .spch-5l.spcht {
                font-size: 24px;
                top: -1.7em;
                transition: font-size 0.218s ease-out
            }

            .permission-bar {
                margin-top: -100px;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                width: 500px;
                transition: opacity 0.218s ease-in,margin-top .4s ease-in
            }

            .s2wfp .permission-bar {
                margin-top: -300px;
                opacity: 1;
                transition: opacity .5s ease-out 0.218s,margin-top 0.218s ease-out 0.218s
            }

            .permission-bar-gradient {
                box-shadow: 0 1px 0px #4285f4;
                height: 80px;
                left: 0;
                margin: 0;
                opacity: 0;
                pointer-events: none;
                position: fixed;
                right: 0;
                top: -80px;
                transition: opacity 0.218s,box-shadow 0.218s
            }

            .s2wfp .permission-bar-gradient {
                box-shadow: 0 1px 80px #4285f4;
                opacity: 1;
                pointer-events: none;
                animation: allow-alert .75s 0 infinite;
                animation-direction: alternate;
                animation-timing-function: ease-out;
                transition: opacity 0.218s,box-shadow 0.218s
            }

            .f6F9Be {
                position: absolute;
                bottom: 0;
                width: 100%
            }

            .fbar a {
                text-decoration: none;
                white-space: nowrap
            }

            .fbar {
                margin-left: -27px
            }

            .Fx4vi {
                padding-left: 27px;
                margin: 0 !important
            }

            #fsl {
                white-space: nowrap
            }

            .f6F9Be {
                background: #171717;
                line-height: 40px;
                padding-bottom: 12px
            }

            .f6F9Be.TrMVnc {
                padding-top: 12px
            }

            .f6F9Be.dc8jac {
                padding-top: 24px
            }

            .B4GxFc {
                margin-left: var(--center-abs-margin);
            }

            .fbar p,.fbar a {
                color: #999da2
            }

            .fbar a:hover {
                color: #bdc1c6
            }

            .fbar {
                font-size: 14px
            }

            .RLQCVb {
                line-height: 40px
            }

            .RLQCVb a {
                cursor: pointer;
                font-weight: bold;
                text-decoration: none
            }

            .SLbK8e {
                max-height: 16px;
                vertical-align: text-top
            }

            .b0KoTc {
                color: #9aa0a6;
                padding-left: 27px
            }

            .b2hzT {
                border-bottom: 1px solid #3c4043
            }

            .Q8LRLc {
                font-size: 15px
            }

            .known_loc {
                forced-color-adjust: none;
                background: #4487f6
            }

            @media (prefers-color-scheme: dark) and (forced-colors:active) {
                .known_loc {
                    background:Highlight
                }
            }

            .unknown_loc {
                background: #9aa0a6
            }

            .smiUbb img {
                margin-right: 4px
            }

            .smiUbb {
                margin-left: var(--center-abs-margin);
                line-height: 15px;
                color: #999da2;
            }

            #swml {
                display: inline-block;
                margin-left: 13px;
                padding-left: 16px;
                border-left: 1px solid #3c4043
            }

            .KwU3F {
                color: #8ab4f8
            }

            .GNm3Qb {
                display: inline-block
            }

            .xSQxL {
                color: #8ab4f8;
                cursor: pointer;
                display: inline-block
            }

            .HDOrGf {
                line-height: 40px
            }

            .EYqSq {
                margin: 6px 4px 9px 0;
                border-radius: 100%;
                display: inline-block;
                height: 10px;
                vertical-align: middle;
                width: 10px
            }

            .dfB0uf {
                color: #bdc1c6;
                font-weight: bold
            }

            .OosGzb {
                width: 376px
            }

            .U8shWc {
                background-color: transparent;
                border: none;
                border-radius: 8px;
                border-radius: 8px;
                box-sizing: border-box;
                cursor: pointer;
                display: inline-block;
                font-size: 14px;
                font-weight: 500;
                padding-top: 6px;
                padding-bottom: 3px;
                min-width: 88px;
                position: relative;
                text-decoration: none !important;
                -webkit-user-select: none;
                white-space: nowrap
            }

            .U8shWc:disabled,.U8shWc[disabled]:not([disabled=false]) {
                pointer-events: none
            }

            .U8shWc.fSXIc {
                min-width: 64px
            }

            .U8shWc.Vy8nid {
                color: #bdc1c6
            }

            .Vy8nid:hover {
                background-color: rgba(102,102,102,.2)
            }

            .Vy8nid:focus {
                background-color: rgba(102,102,102,.2)
            }

            .Vy8nid:active {
                background-color: rgba(102,102,102,.4)
            }

            .U8shWc.Vy8nid:disabled,.U8shWc.Vy8nid[disabled]:not([disabled=false]) {
                color: rgba(255,255,255,.26) !important
            }

            .U8shWc.hpZDWd {
                color: #000
            }

            .hpZDWd:hover {
                background-color: rgba(204,204,204,.15)
            }

            .hpZDWd:focus {
                background-color: rgba(204,204,204,.15)
            }

            .hpZDWd:active {
                background-color: rgba(204,204,204,.25)
            }

            .U8shWc.hpZDWd:disabled,.U8shWc.hpZDWd[disabled]:not([disabled=false]) {
                color: rgba(0,0,0,.3) !important
            }

            .Omzzbd {
                white-space: normal
            }

            .Z7swgb {
                padding: 14px 0
            }

            .ozC9Cd {
                color: #fff;
                padding-top: 4px;
                margin-bottom: -4px
            }
        </style>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                var xsrfTokens = '{\x22UPgwmc\x22:\x22ALook6x2uVAM94HAi9AsGKM13hs-4etlbg:1704440154718\x22}';
                google.xsrf = JSON.parse(xsrfTokens);
            }
            )();
        </script>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                google.ldi = {};
                google.pim = {};
                (function() {
                    var a = google.ldi || {}, b;
                    for (b in a)
                        if (a.hasOwnProperty(b)) {
                            var c = document.getElementById(b) || document.documentElement.querySelector('img[data-iid="' + b + '"]');
                            c && Number(c.getAttribute("data-atf")) & 1 && (c.setAttribute("data-deferred", "2"),
                            c.src = a[b])
                        }
                    ;
                }
                ).call(this);
            }
            )();
        </script>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                google.xjs = {
                    ck: 'xjs.s.OZxnikXpDHs.L.W.O',
                    combam: 'ACAAACoQAAAAAAAAAAAAAABAAAAAAAAEISAcMtkUB_DLIABAABgAAAGqikKAQwCBgM9_QgAAAAAAAEyAwACQBZAKP0MAAMAEqgDsAAAAACDYD0QBAB4EEAAQAwAAIENDIfiAEFACAgAAAMgDgOcBDAcRHgAAAAAAAAAAAAAEMEEwOCD9URAAAQAAAAAAAAAAAABS0uSlQAIAag',
                    cs: 'ACT90oHxwcZD5YBn3NjMI3DV96SSq5fQaA',
                    cssam: 'ACAAACoQAAAAAAAAAAAAAABAAAAAAAAEACAcMNkUBvDIIAAAABgAAAAgAAAAAwCAAAAAAAAAAAAAAACAwAAQBJAKP0EAAMAEqgDsAAAAAAAIAEQBAB4EEAAQAgAAIAMBIfiAEAAAAAAAAAABAAAADAAACAAAAAAAAAAAAAAAAAAAAAD8UQAAAAAAAAAAAAAAAABAAAAEQAIAag',
                    cssopt: false,
                    csss: 'ACT90oG7jod-Jd8TRn7goRzlpdGD_yCDlQ',
                    excm: ['NsEUGe', 'y25qZb', 'AD6AIb', 'fNMhz', 'bXyZdf', 'ZrXR8b', 'du3Q4e', 'ABxRVc', 'rL2AR', 'yChgtb', 'qngJBf', 'cKV22c', 'YuNOCb', 'JxE93', 'ST8mye', 'VZLyBe', 'U3Ovcc', 'TO0csb', 'Oa7Qpb', 'zs9f9d', 'tzTB5', 'XHo6qe', 'FmnE6b', 'jkRPje', 'PoJj8d', 'KzZUob', 'ak946', 'TurKxc', 'PvSBGf', 'Ok4XMd', 'Trirbc', 'eTv59e', 'hfJ9hb'],
                    sepam: false,
                    sepcss: false
                };
            }
            )();
        </script>
        <script nonce="x9iHkhRHZETt-9nytNuh5g">
            (function() {
                google.kEXPI = '0,3700278,671,236,448728,12031,39938,52274,62298,2404,33507,90073,94392,24609,25788,24673,113078,22760,137603,5021,9208,19334,21623,42265,5217304,7228,1305,8791988,20759384,32487958,7794,14363,1856,17202,5338,13399,10539,33538,2789,10155,6,88,4948,1865,4023,1092,547,3,2290,10429,1519,1554,666,1921,2915,6908,2247,1548,248,315,8172,210,808,175,1725,256,730,378,1948,58,1482,2186,712,654,286,46,301,409,6619,290,4846,1631,667,532,134,78,793,2215,204,1222,262,266,270,14,484,435,305,11,2896,2947,589,176,4478,229,1092,316,1337,889,284,349,151,57,825,54,1813,1332,1152,21730592,2761';
            }
            )();
            (function() {
                var u = '/xjs/_/js/k\x3dxjs.s.vi.sATlLnWdPaQ.O/am\x3dACAAACoQAAAAAAAAAAAAAABAAAAAAAAEISAcMtkUB_DLIABAABgAAAGqikKAQwCBgM9_QgAAAAAAAEyAwACQBZAKP0MAAMAEqgDsAAAAACDYD0QBAB4EEAAQAwAAIENDIfiAEFACAgAAAMgDgOcBDAcRHgAAAAAAAAAAAAAEMEEwOCD9URAAAQAAAAAAAAAAAABS0uSlQAIAag/d\x3d1/ed\x3d1/dg\x3d2/br\x3d1/rs\x3dACT90oGXwd5kSHs36lMAYdR_sYFYqChaaw/ee\x3dcEt90b:ws9Tlc;qddgKe:x4FYXe,d7YSfd;yxTchf:KUM7Z;dtl0hd:lLQWFe;eHDfl:ofjVkb;qaS3gd:yiLg6e;nAFL3:NTMZac,s39S4;oGtAuc:sOXFj;iFQyKf:vfuNJf,QIhFr;SNUn3:ZwDk9d,x8cHvb;io8t5d:sgY6Zb;Oj465e:KG2eXe,KG2eXe;Erl4fe:FloWmf,FloWmf;JsbNhc:Xd8iUd;sP4Vbe:VwDzFe;kMFpHd:OTA3Ae;uY49fb:COQbmf;Pjplud:PoEs9b,EEDORb;QGR0gd:Mlhmy;a56pNe:JEfCwb;Me32dd:MEeYgc;wR5FRb:TtcOte,O1Gjze;pXdRYb:JKoKVe;dIoSBb:ZgGg9b;EmZ2Bf:zr1jrb;NSEoX:lazG7b;eBAeSb:Ck63tb;WCEKNd:I46Hvd;wV5Pjc:L8KGxe;EVNhjf:pw70Gc;sTsDMc:kHVSUb;wQlYve:aLUfP;zOsCQe:Ko78Df;KcokUb:KiuZBf;kbAm9d:MkHyGd;g8nkx:U4MzKc;YV5bee:IvPZ6d;IoGlCf:b5lhvb;w9w86d:dt4g2b;ESrPQc:mNTJvc;bFZ6gf:RsDQqe;JXS8fb:Qj0suc;UyG7Kb:wQd0G;LsNahb:ucGLNb;xBbsrc:NEW1Qc;tosKvd:ZCqP3;vfVwPd:lcrkwe;GleZL:J1A7Od;bcPXSc:gSZLJb;VN6jIc:ddQyuf;oUlnpc:RagDlc;CxXAWb:YyRLvc;VGRfx:VFqbr;EABSZ:MXZt9d;DpcR3d:zL72xf;NPKaK:SdcwHb;LBgRLc:XVMNvd,SdcwHb;ZWEUA:afR4Cf;qZx2Fc:j0xrE;lzgfYb:PI40bd;pNsl2d:j9Yuyc;VsAqSb:PGf2Re;R9Ulx:CR7Ufe;kY7VAf:d91TEb;KpRAue:Tia57b;jY0zg:Q6tNgc;coJ8e:KvoW8;oSUNyd:fTfGO,fTfGO,pnvXVc;SMDL4c:fTfGO,pnvXVc;aZ61od:arTwJ;w4rSdf:XKiZ9;h3MYod:cEt90b;eO3lse:nFClrf;zaIgPb:Qtpxbd;HMDDWe:G8QUdb;ShpF6e:N0pvGc;k2Qxcb:XY51pe;IBADCc:RYquRb;pKJiXd:VCenhc;rQSrae:C6D5Fc;kCQyJ:ueyPK;qavrXe:zQzcXe,mYbt1d;TxfV6d:YORN0b;UDrY1c:eps46d;F9mqte:UoRcbe;Nyt6ic:jn2sGd;w3bZCb:ZPGaIb;G0KhTb:LIaoZ;XUezZ:sa7lqb;aAJE9c:WHW6Ef;V2HTTe:RolTY;Wfmdue:g3MJlb;imqimf:jKGL2e;BgS6mb:fidj5d;gtVSi:ekUOYd;KQzWid:ZMKkN;UVmjEd:EesRsb;z97YGf:oug9te;AfeaP:TkrAjf;eBZ5Nd:audvde;OgagBe:cNTe0;SLtqO:Kh1xYe;VOcgDe:YquhTb;uuQkY:u2V3ud;WDGyFe:jcVOxd;trZL0b:qY8PFe;VxQ32b:k0XsBb;DULqB:RKfG5c;Np8Qkd:Dpx6qc;cFTWae:gT8qnd;gaub4:TN6bMe;hjRo6e:F62sG;BjwMce:cXX2Wb;yGxLoc:FmAr0c;pj82le:mg5CW;dLlj2:Qqt3Gf;qGV2uc:HHi04c;R2kc8b:ALJqWb;EnlcNd:WeHg4;Q1Ow7b:x5CSu;okUaUd:wItadb;xbe2wc:wbTLEd;KOxcK:bFOvTc;G6wU6e:hezEbd;uknmt:GkPrzb;U96pRd:FsR04;PqHfGe:im2cZe;heHB1:sFczq;Fmv9Nc:O1Tzwc;hK67qb:QWEO5b;BMxAGc:E5bFse;R4IIIb:QWfeKf;whEZac:F4AmNb;tH4IIe:Ymry6;lkq0A:JyBE3e;daB6be:lMxGPd;LEikZe:byfTOb,lsjVmc/m\x3dattn,cdos,gwc,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl';
                var amd = 0;
                var e = this || self
                  , f = function(a) {
                    return a
                };
                var g;
                var h = function(a) {
                    this.g = a
                };
                h.prototype.toString = function() {
                    return this.g + ""
                }
                ;
                var k = {};
                var l = function() {
                    var a = document;
                    var b = "SCRIPT";
                    "application/xhtml+xml" === a.contentType && (b = b.toLowerCase());
                    return a.createElement(b)
                };
                function m(a, b) {
                    a.src = b instanceof h && b.constructor === h ? b.g : "type_error:TrustedResourceUrl";
                    var c, d;
                    (c = (b = null == (d = (c = (a.ownerDocument && a.ownerDocument.defaultView || window).document).querySelector) ? void 0 : d.call(c, "script[nonce]")) ? b.nonce || b.getAttribute("nonce") || "" : "") && a.setAttribute("nonce", c)
                }
                ;function n(a) {
                    a = null === a ? "null" : void 0 === a ? "undefined" : a;
                    if (void 0 === g) {
                        var b = null;
                        var c = e.trustedTypes;
                        if (c && c.createPolicy) {
                            try {
                                b = c.createPolicy("goog#html", {
                                    createHTML: f,
                                    createScript: f,
                                    createScriptURL: f
                                })
                            } catch (d) {
                                e.console && e.console.error(d.message)
                            }
                            g = b
                        } else
                            g = b
                    }
                    a = (b = g) ? b.createScriptURL(a) : a;
                    return new h(a,k)
                }
                ;void 0 === google.ps && (google.ps = []);
                function p() {
                    var a = u
                      , b = function() {};
                    google.lx = google.stvsc ? b : function() {
                        q(a);
                        google.lx = b
                    }
                    ;
                    google.bx || google.lx()
                }
                function r(a, b) {
                    b && m(a, n(b));
                    var c = a.onload;
                    a.onload = function(d) {
                        c && c(d);
                        google.ps = google.ps.filter(function(t) {
                            return a !== t
                        })
                    }
                    ;
                    google.ps.push(a);
                    document.body.appendChild(a)
                }
                google.as = r;
                function q(a) {
                    google.timers && google.timers.load && google.tick && google.tick("load", "xjsls");
                    var b = l();
                    b.onerror = function() {
                        google.ple = 1
                    }
                    ;
                    b.onload = function() {
                        google.ple = 0
                    }
                    ;
                    google.xjsus = void 0;
                    r(b, a);
                    google.aple = -1;
                    google.psa = !0
                }
                ;google.xjsu = u;
                e._F_jsUrl = u;
                setTimeout(function() {
                    0 < amd ? google.caft(function() {
                        return p()
                    }, amd) : p()
                }, 0);
            }
            )();
            window._ = window._ || {};
            window._DumpException = _._DumpException = function(e) {
                throw e;
            }
            ;
            window._s = window._s || {};
            _s._DumpException = _._DumpException;
            window._qs = window._qs || {};
            _qs._DumpException = _._DumpException;
            (function() {
                var t = [8426, 16552, 0, 0, 4194304, 0, 33690688, 95833255, 550238215, 536936448, 537919489, 537965226, 8454339, 17432382, 138497, 538116096, 93847744, 217853504, 201326599, 989866625, 2, 272589696, 31457300, 67109889, 536870915, 545590540, 620824591, 128, 537118720, 472909726, 123152, 0, 0, 79695872, 302220036, 267391, 1, 0, 536870912, 695809172, 704643648, 1];
                window._F_toggles = window._xjs_toggles = t;
            }
            )();
            function _F_installCss(c) {}
            (function() {
                google.jl = {
                    blt: 'none',
                    chnk: 0,
                    dw: false,
                    dwu: true,
                    emtn: 0,
                    end: 0,
                    ico: false,
                    ikb: 0,
                    ine: false,
                    injs: 'none',
                    injt: 0,
                    injth: 0,
                    injv2: false,
                    lls: 'viewport',
                    pdt: 0,
                    rep: 0,
                    snet: true,
                    strt: 0,
                    ubm: false,
                    uwp: true
                };
            }
            )();
            (function() {
                var pmc = '{\x22aa\x22:{},\x22abd\x22:{\x22abd\x22:false,\x22deb\x22:false,\x22det\x22:false},\x22async\x22:{},\x22attn\x22:{},\x22bgd\x22:{\x22ac\x22:true,\x22as\x22:true,\x22at\x22:0,\x22ea\x22:true,\x22ed\x22:0,\x22ei\x22:true,\x22el\x22:true,\x22ep\x22:true,\x22er\x22:true,\x22et\x22:0,\x22eu\x22:false,\x22li\x22:false,\x22wl\x22:false},\x22cdos\x22:{\x22bih\x22:701,\x22biw\x22:1364,\x22cdobsel\x22:false,\x22dpr\x22:\x221\x22},\x22csi\x22:{},\x22d\x22:{},\x22foot\x22:{\x22dv\x22:\x2246tc3g-teGxWUHFnxQKTMX9_pcyIzViAuClUv9L1nQEAAOAeYAAQspMRtQAAAISvFQ9mKv6nOQAAAGiYBOOXTyoPEgAAAA\x22},\x22gf\x22:{\x22pid\x22:196,\x22si\x22:true},\x22gwc\x22:{},\x22hsm\x22:{},\x22jsa\x22:{\x22csi\x22:true,\x22csir\x22:100},\x22kyn\x22:{},\x22lli\x22:{},\x22mb4ZUb\x22:{},\x22mu\x22:{\x22murl\x22:\x22https://adservice.google.com/adsid/google/ui\x22},\x22pHXghd\x22:{},\x22sb_wiz\x22:{\x22onf\x22:\x22EAEy0wEKEAoOV2ViIGNvZGUgbeG6q3UKEAoOQ29kZSBt4bqrdSBDKysKFwoVQ29kZSBtw6B1IGMgdHLDoWkgdGltCiEKH1NoYXJlIGNvZGUgd2ViIEhUTUwgxJHhurlwIGZyZWUKFQoTQ29kZSBtw6B1IHRyw6FpIHRpbQoiCiBTaGFyZSBjb2RlIHdlYiBIVE1MIMSRxqFuIGdp4bqjbgoVChNCw6BpIHThuq1wIGNvZGUgQysrCh0KG0LDoGkgdOG6rXAgY29kZSBDIGPDsyBi4bqjbhBH\x22,\x22scq\x22:\x22\x22,\x22stok\x22:\x22x1tE8dOTIg3vcIB6HR-w4-5JYs4\x22,\x22ueh\x22:\x22d1910b38_265b6214_180aa1f2_29a91cc1_626d7913\x22},\x22sf\x22:{},\x22sonic\x22:{},\x22spch\x22:{\x22ae\x22:\x22Vui l\\u00f2ng ki\\u1ec3m tra micr\\u00f4 c\\u1ee7a b\\u1ea1n.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003ET\\u00ecm hi\\u1ec3u th\\u00eam\\u003C/a\\u003E\x22,\x22ak\x22:\x22\x22,\x22cd\x22:0,\x22fp\x22:false,\x22hl\x22:\x22vi-VN\x22,\x22im\x22:\x22Nh\\u1ea5p v\\u00e0o \\u003Cb\\u003ECho ph\\u00e9p\\u003C/b\\u003E \\u0111\\u1ec3 b\\u1eaft \\u0111\\u1ea7u t\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i\x22,\x22iw\x22:\x22\\u0110ang ch\\u1edd...\x22,\x22lm\x22:\x22\\u0110ang nghe\\u2026\x22,\x22lu\x22:\x22T\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i %1$s kh\\u00f4ng kh\\u1ea3 d\\u1ee5ng\x22,\x22mb\x22:false,\x22ne\x22:\x22Kh\\u00f4ng c\\u00f3 k\\u1ebft n\\u1ed1i Internet\x22,\x22nt\x22:\x22Kh\\u00f4ng th\\u1ec3 d\\u1ecbch \\u0111\\u01b0\\u1ee3c. \\u003Cspan\\u003ETh\\u1eed l\\u1ea1i\\u003C/span\\u003E\x22,\x22nv\x22:\x22Vui l\\u00f2ng ki\\u1ec3m tra micr\\u00f4 v\\u00e0 \\u00e2m l\\u01b0\\u1ee3ng c\\u1ee7a b\\u1ea1n.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003ET\\u00ecm hi\\u1ec3u th\\u00eam\\u003C/a\\u003E\x22,\x22pe\x22:\x22T\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i \\u0111\\u00e3 b\\u1ecb t\\u1eaft.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003EChi ti\\u1ebft\\u003C/a\\u003E\x22,\x22rm\x22:\x22Xin m\\u1eddi n\\u00f3i\x22,\x22s3\x22:false},\x22tl\x22:{\x22rvkey\x22:\x22AIzaSyC_9Rt88UMjzgg5pIVArnfuIVkJx4zCdTY\x22}}';
                google.pmc = JSON.parse(pmc);
            }
            )();
            (function() {
                var r = ['sb_wiz', 'aa', 'abd', 'async', 'bgd', 'foot', 'kyn', 'lli', 'mu', 'pHXghd', 'sf', 'sonic', 'spch', 'tl'];
                google.plm(r);
            }
            )();
            (function() {
                var m = {
                    "Bmu0rE": ["gws-wiz-serp", "", "code mẫu", "", null, 1, 0, 0, 13, "vi", "x1tE8dOTIg3vcIB6HR-w4-5JYs4", "d1910b38265b6214180aa1f229a91cc1626d7913", "WrGXZcTbGIHc1e8P9Y2o8A8", 0, "vi", null, null, null, 3, 5, 8, null, null, 0, 1, 1, 0, 1, 0, 8, -1, null, null, null, 1.15, 0, null, 0, 1, 9, 0, 0, 0, null, 0, null, 1, 1, 0, 0, 1, null, "", 0, 1, 0, -1, null, null, 0, 0, null, 0, 0, 0, "futura_sug_zp_si_0000000_e", null, null, "", 0, null, 1, -1, -1, null, 1, 1, 1, 1000, null, null, 1, ["gws-wiz-serp", "", ""], 1, ["gws-wiz-local", "", ""], 1, ["img", "gws-wiz-img", "i"], 1, ["products-cc", "", "sh"], 1, ["gws-wiz-modeless", "gws-wiz-perspectives", ""], 1, ["hotel-searchbox", "mobile-gws-wiz-hotel", ""], 1, ["gws-wiz-modeless", "", ""], 0, null, 0, 1, 0, null, 1, ["gws-wiz-serp", "", ""], 1, ["gws-wiz-serp", "", ""], 1, ["gws-wiz-serp", "", ""], 0, 0, 1, ["gws-wiz-video", "", "v"], 0, 0, 1, ["gws-wiz-modeless", "", ""], 1, ["gws-wiz-modeless", "", ""]],
                    "Bmu0rI": [3, 0, 0, 0, 0, 0, 10, 0, 0, 0],
                    "Bmu0rM": [6, 3, null, null, 1, 1, 0, 1, 0, 0, 0, 0, 0],
                    "Bmu0rQ": ["spyw", 1, 0],
                    "Bmu0rg": [null, null, null, [null, null, [[[3, null, null, [null, [["lr_", 1, 6], ["lr_lang_1vi", 0, 6]], 0]], [3, null, null, [null, [["qdr_", 1, 6], ["qdr_h", 0, 6], ["qdr_d", 0, 6], ["qdr_w", 0, 6], ["qdr_m", 0, 6], ["qdr_y", 0, 6], ["cdr_opt", 0, 1, [1, "Phạm vi tùy chỉnh...", null, "cdr:1,cd_min:x,cd_max:x", "", "text", "", "", 6, null, [[["q", "code mẫu"], ["sca_esv", "595895911"], ["sxsrf", "AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411"]]], "cdr_opt", "23/05/2004", 0]]], 1]], [3, null, null, [null, [["li_", 1, 6], ["li_1", 0, 6]], 2]]], null, ["tbs"]]], null, null, [null, [["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Tất cả", 1, 0, 1, null, null, "WEB", [0, 2], null, null, 0], ["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003disch\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Hình ảnh", 0, 0, 1, null, null, "IMAGES", [6, 2], null, null, 6], ["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003dvid\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Video", 0, 0, 1, null, null, "VIDEOS", [13, 2], null, null, 13], ["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003dshop\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Mua sắm", 0, 0, 1, null, null, "SHOPPING", [12, 2], null, null, 12, 1], ["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003dbks\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Sách", 0, 0, 1, null, null, "BOOKS", [2, 2], null, null, 2]], [["/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003dnws\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Tin tức", 0, 0, 1, null, null, "NEWS", [10, 2], null, null, 10], ["https://www.google.com/travel/flights?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026tbm\u003dflm\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026source\u003dlnms", null, null, "Chuyến bay", 0, 0, 1, null, null, "FLIGHTS", [20, 2], null, null, 20, 1], ["//www.google.com/finance", null, null, "Tài chính", 0, 0, 1, null, null, "FINANCE", [22, 2], null, null, 22]]]],
                    "Bmu0r0": [4, 1, null, null, 1, 1, 0, 0, 0, 0, 0, 0, 0],
                    "Bmu0r4": ["", 6, 0],
                    "Bmu0r8": ["", 4, 0],
                    "Bmu0sE": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:HBujmRzuDaMJ:https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["Bài tập C++ có lời giải (code mẫu) - QuanTriMang.com", "https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335", "Bài tập C++ có lời giải (code mẫu) - QuanTriMang.com"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["Bài tập C++ có lời giải (code mẫu) - QuanTriMang.com", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxICCAAaACIAKgAyBggBEgJ2bjoAQgQIARBCSgBaAHIAegA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fquantrimang.com%2Fhoc%2Fbai-tap-c-co-loi-giai-code-mau-143335\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0sM": ["https://quantrimang.com/hoc/bai-tap-c-co-loi-giai-code-mau-143335", "Bài tập C++ có lời giải (code mẫu)", "Yêu cầu: Mỗi lần chỉ chuyển 1 tầng, chỉ được dùng các vị trí A, B, C để đặt các tầng tháp, không được đặt tầng lớn lên trên tầng nhỏ. Hàm main sử dụng hàm này ...", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6ywoiIwBL7z2exJdamReTz0vUV_Ng:1704440154648"],
                    "Bmu0sI": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:w7JI-d0omnkJ:https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["9 website cung cấp code mẫu tốt nhất dành cho lập trình viên", "https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/", "9 website cung cấp code mẫu tốt nhất dành cho lập trình viên"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["9 website cung cấp code mẫu tốt nhất dành cho lập trình viên", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Ffunix.edu.vn%2Fchia-se-kien-thuc%2Fwebsite-code-mau%2F\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0sQ": ["https://funix.edu.vn/chia-se-kien-thuc/website-code-mau/", "9 website cung cấp code mẫu tốt nhất dành cho lập trình viên", "9 website cung cấp code mẫu tốt nhất dành cho lập trình viên · 1. Stack Overflow · 2. SourceForge.net · 4. CodeProject.com · 5. DevX.com · 6.", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6ywoiIwBL7z2exJdamReTz0vUV_Ng:1704440154648"],
                    "Bmu0sA": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:74cqrg7kVfAJ:https://mikotech.vn/code-web-mau/\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["10 Code web mẫu đẹp mắt, miễn phí các lập trình viên nên có", "https://mikotech.vn/code-web-mau/", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://mikotech.vn/code-web-mau/", "10 Code web mẫu đẹp mắt, miễn phí các lập trình viên nên có"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["10 Code web mẫu đẹp mắt, miễn phí các lập trình viên nên có", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://mikotech.vn/code-web-mau/"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxICCAAaACIAKgAyBggBEgJ2bjoAQgQIARBCSgBaAHIAegA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fmikotech.vn%2Fcode-web-mau%2F\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0sU": ["https://mikotech.vn/code-web-mau/", "10 Code web mẫu đẹp mắt, miễn phí các lập trình viên nên ...", "10 code web mẫu sau đây có thể giúp các lập trình viên cải thiện hiệu suất công việc và rút ngắn thời gian làm web chuyên nghiệp.", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6ywoiIwBL7z2exJdamReTz0vUV_Ng:1704440154648"],
                    "Bmu0sg": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:ObUp5Kr7VC8J:https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["Bài tập C++ có giải (code mẫu) về biến, kiểu dữ liệu và toán tử", "https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623", "Bài tập C++ có giải (code mẫu) về biến, kiểu dữ liệu và toán tử"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["Bài tập C++ có giải (code mẫu) về biến, kiểu dữ liệu và toán tử", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fquantrimang.com%2Fhoc%2Fbai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0tE": ["https://quantrimang.com/hoc/bai-tap-c-co-giai-code-mau-ve-bien-kieu-du-lieu-va-toan-tu-143623", "Bài tập C++ có giải (code mẫu) về biến, kiểu dữ liệu và ...", "Bài tập C++ về toán tử · Viết một chương trình trong C++ để in tổng của hai số. · Tìm tổng, hiệu, tích và thương của hai số nguyên và in kết quả ...", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0sw": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho Các ...", "https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb", "[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho Các ..."]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho Các ...", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fybox.vn%2Fky-nang%2Ftoptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0tA": ["https://ybox.vn/ky-nang/toptip-top-10-website-code-mau-chuyen-nghiep-cho-cac-lap-trinh-vien-64809d04973df035f0943aeb", "[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho ...", "[TopTip] Top 10 Website Code Mẫu Chuyên Nghiệp Cho Các Lập Trình Viên · 1. Stackoverflow.com · 2. Sourceforge.net · 3. CodeGuru.com · 4. Codeproject.com · 5.", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0so": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:QTOqsIxlXMIJ:https://api.tphcm.gov.vn/ChiTietLgsp/id/224\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["Code Example", "https://api.tphcm.gov.vn/ChiTietLgsp/id/224", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://api.tphcm.gov.vn/ChiTietLgsp/id/224", "Code Example"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["Code Example", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://api.tphcm.gov.vn/ChiTietLgsp/id/224"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fapi.tphcm.gov.vn%2FChiTietLgsp%2Fid%2F224\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0s0": ["https://api.tphcm.gov.vn/ChiTietLgsp/id/224", "Code Example", "CODE EXAMPLE. Code mẫu .Net. using RestSharp;. using System;. using System.Collections.Generic;. using System.Configuration;. using System.Linq;.", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0tI": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:XebSR4aiLEIJ:https://api.tphcm.gov.vn/ChiTietLgsp/id/117\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["Code mẫu .Net", "https://api.tphcm.gov.vn/ChiTietLgsp/id/117", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://api.tphcm.gov.vn/ChiTietLgsp/id/117", "Code mẫu .Net"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["Code mẫu .Net", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://api.tphcm.gov.vn/ChiTietLgsp/id/117"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fapi.tphcm.gov.vn%2FChiTietLgsp%2Fid%2F117\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0tQ": ["https://api.tphcm.gov.vn/ChiTietLgsp/id/117", "Code mẫu .Net", "API đồng bộ thông tin đăng ký kết hôn. Code example. Code mẫu .Net. API Method Get. API Method POST. Code mẫu java. API Method Get. API Method POST. Danh sách ...", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0tM": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:hIzbgpNwdaUJ:https://didongviet.vn/dchannel/cach-lam-code-trai-tim/\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["10+ cách làm code trái tim của Thủ Khoa Lý cực kỳ đơn giản", "https://didongviet.vn/dchannel/cach-lam-code-trai-tim/", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://didongviet.vn/dchannel/cach-lam-code-trai-tim/", "10+ cách làm code trái tim của Thủ Khoa Lý cực kỳ đơn giản"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["10+ cách làm code trái tim của Thủ Khoa Lý cực kỳ đơn giản", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://didongviet.vn/dchannel/cach-lam-code-trai-tim/"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxICCAAaACIAKgAyBggBEgJ2bjoAQgQIARBCSgBaAHIAegA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fdidongviet.vn%2Fdchannel%2Fcach-lam-code-trai-tim%2F\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0tU": ["https://didongviet.vn/dchannel/cach-lam-code-trai-tim/", "10+ cách làm code trái tim của Thủ Khoa Lý cực kỳ đơn giản", "Code mẫu trái tim cơ bản. Đây chính là những dòng code trước tiên nổi rần rần trên cộng đồng mạng khi phim đã ra mắt tập đầu tiên. Cụ thể, hình ...", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0ss": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:_8Xw-HVhrqcJ:https://codelearn.io/sharing/vong-lap-game-cac-code-mau\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["Vòng Lặp Game - Các Code Mẫu - CodeLearn", "https://codelearn.io/sharing/vong-lap-game-cac-code-mau", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://codelearn.io/sharing/vong-lap-game-cac-code-mau", "Vòng Lặp Game - Các Code Mẫu - CodeLearn"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["Vòng Lặp Game - Các Code Mẫu - CodeLearn", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://codelearn.io/sharing/vong-lap-game-cac-code-mau"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fcodelearn.io%2Fsharing%2Fvong-lap-game-cac-code-mau\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0s8": ["https://codelearn.io/sharing/vong-lap-game-cac-code-mau", "Vòng Lặp Game - Các Code Mẫu", "Một vòng lặp trò chơi cần hai mảnh khóa cần để tâm: không chặn đầu vào người dùng và khả năng thích nghi với sự trôi dạt của thời gian. Đầu vào ...", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0sk": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [[[null, null, null, null, null, ["", "https://webcache.googleusercontent.com/search?q\u003dcache:izePRoudRBIJ:https://writeblabla.com/blog/tags/code-mau/\u0026hl\u003dvi\u0026gl\u003dvn", null, [null, [32, null, 2]], null, null, null, [["Bản\u0026nbsp;lưu"]]]]]], null, null, null, "", null, "WEB_RESULT_INNER", [[[null, null, null, 3, [[null, null, null, ["code mẫu - Phan Tấn Dũng Blog", "https://writeblabla.com/blog/tags/code-mau/", null, null, null, " ", null, null, null, null, null, ["mslc"], 35, 1]]]], [null, null, null, 2, [null, [null, null, 5, "https://writeblabla.com/blog/tags/code-mau/", "code mẫu - Phan Tấn Dũng Blog"]]], [null, null, null, 6], [null, null, null, 4, [null, null, ["code mẫu - Phan Tấn Dũng Blog", "WEB_RESULT_INNER", 0]]]], null, null, [1, "https://writeblabla.com/blog/tags/code-mau/"]], 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d2586\u0026ri\u003dCgoSCAoEY29kZRADCgsSCQoFbeG6q3UQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgByAHoA\u0026fd\u003dGgIIAw\u0026dis\u003dEAE\u0026url\u003dhttps%3A%2F%2Fwriteblabla.com%2Fblog%2Ftags%2Fcode-mau%2F\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [], 0, 0, 0, 0, []],
                    "Bmu0s4": ["https://writeblabla.com/blog/tags/code-mau/", "code mẫu - Phan Tấn Dũng Blog", "Các bài viết hướng dẫn code mẫu các mẫu code mẫu đơn giản cần cho tất cả các lập trình viên.", 0, "vi", "VN", [null, 0, null, null, "ngockhoannk@gmail.com"], "/s?tbm\u003dmap\u0026gs_ri\u003dmaps\u0026suggest\u003dp", "ALook6zIDp6pD_Qewc66a5DoBJryGtYJUw:1704440154661"],
                    "Bmu0sY": [null, null, null, null, null, null, null, null, null, null, null, null, 0, [], null, null, null, "", 0, "EXPLORE_UNIVERSAL_BOTTOM_BLOCK", null, 0, [null, null, null, null, null, null, [null, null, null, "/search/about-this-result?origin\u003dwww.google.com\u0026ons\u003d3560\u0026ri\u003d\u0026fd\u003dCgwKBAgwSBAKBAg_UEISBAoCCA8aAggD\u0026dis\u003dEAE\u0026dm\u003d1\u0026sa\u003d1\u0026hl\u003dvi_VN\u0026gl\u003dVN"], "https://www.google.com"], 0, [1354], 0, 0, 0, 0, []],
                    "Bmu0sc": [],
                    "Bmu0rs": ["code mẫu", null, null, "all", 350, 5, 1, null, null, 0, null, 1, 1, null, null, null, "all", 0, "srp_1", null, null, 10, "/search?q\u003dcode+m%E1%BA%ABu\u0026sca_esv\u003d595895911\u0026sxsrf\u003dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\u0026ei\u003dWrGXZcTbGIHc1e8P9Y2o8A8\u0026start\u003d10\u0026sa\u003dN", 0, 0, null, 0, null, null, 0, null, null, null, null, null, null, null, 0, null, null, null, null, null, null, null, null, null, null, null, 0, "", "", null, null, null, null, "NONE", null, null, null, null, 0, null, "NONE", 0, 0, 0, "", 0, [null, "Aad95RoDvLNc9nlhpQhy6Nq4Nq8DOsK-kISdGNZtjuWN42VdUHTsvWdq5cpqst6L6TBJSdxTAVoOIJZzUfMjXwYPcC1BPuW8ONBwEA"], 1, 0, null, null, 0, 0, 0, 0, 1, 0, null, 0, 10, 0, 5],
                    "Bmu0rU": [null, null, 1, null, null, null, null, null, null, null, 3, null, null, null, null, null, null, null, null, null, 0, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, null, 1, null, null, ["86400000", "604800000", 2], null, null, null, null, null, null, null, null, null, null, null, null, null, 1, 1, null, null, null, null, null, null, null, null, 1, "DESKTOP_CHROME"],
                    "Bmu0rY": ["358585872441558158"],
                    "Bmu0rc": [null, null, null, 1, ["bshqp", "bshwcqp", "rimc", "rime"]],
                    "Bmu0rk": [13, "AeMu1zcHE8g_KDs7kIIUyD__9IDOssv9P6af4BPjy_0_", "3563806597960685957"],
                    "Bmu0ro": [1, null, null, 1, 0, 0, 0, null, 0, 0],
                    "Bmu0rw": [null, null, 1, null, null, null, 1, null, ""],
                    "tq7Pxb": [[["q49bvd", 0], ["BKzT2", 1], ["LrGvF", 1], ["VrsW7", 0], ["VXIo7d", null, "8px"], ["LACYrf", 0], ["TW7Aod", 1], ["ziwEW", null, "#9aa0a6"], ["SA0BPe", 1], ["IBWrx", null, null, 18], ["AoIPu", 1], ["EgTnfe", 1], ["CgDdte", 1], ["I6R5lf", null, "#303134"], ["v4iQCe", null, "#4487f6"], ["IfdAAd", null, "#9aa0a6"], ["Sa67Pc", null, "rgba(0,0,0,0.6)"], ["OmYlge", null, "#219540"], ["H4gDmf", null, "#ff7769"], ["KkPbyc", null, "#8a4a00"], ["o28sBd", 0], ["QQVhX", 0], ["ULXB9b", 0], ["r9V7hf", 0], ["FEmOOb", null, null, 40], ["cWwp7b", 0], ["wsRfI", 0], ["WkjuOe", 0], ["h6eQZc", 0], ["b0Jode", 0], ["WitVqe", 1], ["YjL9Ce", 0], ["mIjP6d", 0], ["m8l8td", null, "CARET"], ["JyBo2c", 0], ["bmQ7Rb", 0], ["xT28q", 0], ["VBSc8c", 1], ["qdoinb", null, "#9aa0a6"], ["HjM8R", null, "#303134"], ["JdPOaf", 0], ["bDOvJc", 0], ["HCImye", 0], ["zBxT5", 1], ["m4Aoxd", 0], ["SOoLvb", null, null, 8], ["MRtzJd", 0], ["kjIzLb", 1], ["voc95c", 0], ["qmcJmd", null, null, 6], ["aZFNNe", 1], ["Rvxsx", null, "1px solid #5f6368"], ["xNPzic", null, "#202124"], ["rzzybc", null, "#f28b82"], ["zRpUk", null, "#6283ff"], ["sBpVac", null, "rgba(255,255,255,.26)"], ["JuqxTb", null, "#bdc1c6"], ["Fcb4A", null, "#8ab4f8"], ["A1m1qe", 1], ["yqqDTc", 0], ["uDSxz", null, "#3c4043"], ["oHxv0d", null, null, 16], ["Y6rSjc", 1], ["ghpS4b", null, "#15294b"], ["Zun3Ef", 0], ["AP8pqf", null, "#3c4043"], ["ZMIIMe", 1], ["yHlFbb", null, "rgba(255,255,255,.4)"], ["OL2x3c", 0], ["wFGKdc", 1], ["ywhzh", 0], ["HIMA4e", 0], ["m2hzy", 0], ["Lxmjn", 1], ["FydCC", 1], ["wku5sd", 0], ["pbvXic", 1], ["j7hDXe", 0], ["rRH6Ed", null, "#8ab4f8"], ["DU6xHc", 0], ["XuC5Td", null, null, 24], ["vhNSCe", 0], ["lYyelb", null, "rgba(255,255,255,.54)"], ["Keb5Pb", 0], ["oY6Swe", 0], ["cGEPwe", 0], ["vNcih", 0], ["WOsyy", 0], ["Fa0cAb", 0], ["g2CbC", null, null, 1], ["q8rKTc", 0], ["gSzSKd", null, ""], ["G0mITe", 0], ["pnaHhb", 0], ["rEYaZe", null, ""], ["xXrl9", null, ""], ["V4p6F", 0], ["VTTQYb", 0], ["htN2H", 0], ["HvnEEd", 0], ["rZHtfe", 0], ["uXUEhb", 0], ["mNmrAb", null, "#3c4043"], ["JJFoUe", 1], ["o40Eoc", 0], ["irjI3c", 0], ["xnaMFd", null, "feedback"], ["ptnYGd", null, "[[[\"box-shadow\",\"box-shadow\"],[\"box-sizing\",\"box-sizing\"],[\"keyframes\",\"keyframes\"],[\"border-radius\",\"border-radius\"],[\"transform\",\"transform\"],[\"transform-origin\",\"transform-origin\"],[\"flex-direction\",\"flex-direction\"],[\"flex-grow\",\"flex-grow\"],[\"flex\",\"flex\"]]]"]]]
                };
                var a = m;
                if (window.W_jd)
                    for (var b in a)
                        window.W_jd[b] = a[b];
                else
                    window.W_jd = a;
            }
            )();
            (function() {
                window.WIZ_global_data = {
                    "zChJod": "%.@.]",
                    "SNlM0e": "ALeMFfRlg2BLZf6hvd6rTiJgtWTU:1704440154726",
                    "NCGTLe": "%.@.\"ANIgHNnpZ4yffXGfxkRtUtJEh8mYc6Z0XOWAKdMp0ixaToq0RbkwqOsMBmLUCBEv/06s6P9e+jEf/1J10pbup9kp8AhuKFA1/g\\u003d\\u003d\"]",
                    "oxN3nb": {
                        "1": false
                    },
                    "Im6cmf": "/wizrpcui/_/WizRpcUi",
                    "GWsdKe": "vi-VN",
                    "QrtxK": "0",
                    "S06Grb": "100851705259503639002",
                    "S6lZl": "89978449",
                    "Yllh3e": "%.@.1704440154404932,133524993,4262070005]",
                    "w2btAe": "%.@.\"100851705259503639002\",\"100851705259503639002\",\"0\",null,null,null,1]",
                    "eptZe": "/wizrpcui/_/WizRpcUi/",
                    "LVIXXb": "1"
                };
                window.IJ_values = {
                    "eG8Zqf": 1.0,
                    "IvNqzc": true,
                    "ZAVjNb": false,
                    "oI8LH": false,
                    "IXFWPb": false,
                    "vSjUZd": 24,
                    "P59QTc": false,
                    "gfq1Ic": false,
                    "HKzGBb": false,
                    "B4LUOc": false,
                    "q9jm5e": false,
                    "zIfn3e": false,
                    "bs2drc": false,
                    "hnypGb": false,
                    "yys2yc": false,
                    "Rbaz9c": false,
                    "SoPmHd": true,
                    "lCCykc": false,
                    "ro3IRe": false,
                    "eflcTd": false,
                    "NdHRde": false,
                    "MlUHWc": false,
                    "CzxWj": false,
                    "ZYBs3c": false,
                    "Wn9ite": false,
                    "kyqNwe": false,
                    "ucii4d": false,
                    "GL2pid": false,
                    "QRQY4b": false,
                    "vwAn2d": false,
                    "hK1XQe": "#dadada",
                    "O3122d": 14,
                    "CUOpOb": 18,
                    "KrguY": "#3c4043",
                    "DONkrd": "#fff",
                    "AILAfd": "#202124",
                    "WdWVbc": false,
                    "Tv95nc": false,
                    "urls1d": false,
                    "mhcbZb": false,
                    "ogmk0d": false,
                    "RK9az": false,
                    "T62UHb": false,
                    "jCekpb": false,
                    "cTU58": false,
                    "kRerQb": false,
                    "oS0end": false,
                    "AoIPu": true,
                    "CieUQe": true,
                    "HCMJkf": true,
                    "zNiNDd": false,
                    "EsWLY": false,
                    "XP4Noc": false,
                    "jqcxU": "#8ab4f8",
                    "toVELc": "#f8f9fa",
                    "V1TJEb": "#8ab4f8",
                    "eavN9c": 36,
                    "XuC5Td": 24,
                    "ivyWed": 28,
                    "psmQyf": 6,
                    "osNyZ": 1.0,
                    "L6WyEf": true,
                    "tswRXd": "none",
                    "vq4Rhf": true,
                    "mtmrtb": "1px 1px 15px 0px #171717",
                    "hOdcKb": false,
                    "vkQXZ": "#202124",
                    "U2GTk": "#202124",
                    "WgRLme": "#3c4043",
                    "QcZxSd": "#bdc1c6",
                    "g4ToDf": "0 1px 2px rgba(60,64,67,.3), 0 2px 6px 2px rgba(60,64,67,.15)",
                    "AsC4Mb": "#9aa0a6",
                    "mub7Fd": "#3c4043",
                    "z2SQwf": "#80868b",
                    "ob4Y0c": "#767c80",
                    "M1fk3b": "#424548",
                    "gWINCf": "#bdc1c6",
                    "I6R5lf": "#303134",
                    "KCMXVb": "#e8eaed",
                    "vzRvgb": "#8ab4f8",
                    "HNLwz": "#aecbfa",
                    "uD3Lwc": "#aecbfa",
                    "TqDTGf": "#aecbfa",
                    "m7EnTc": "#d2e3fc",
                    "jyEUXe": "#8ab4f8",
                    "QyzZ8e": "#202124",
                    "CFgsb": "#202124",
                    "lYyelb": "rgba(255,255,255,.54)",
                    "uWxHhb": "#000",
                    "m0RlKb": false,
                    "wFGKdc": true,
                    "klgere": "none",
                    "gHo7b": "#424548",
                    "VBSc8c": true,
                    "oX2r2c": true,
                    "WitVqe": true,
                    "JuXRyb": true,
                    "zsYZK": "#3c4043",
                    "Pi4f8d": false,
                    "nNHNPc": false,
                    "VD4u1d": false,
                    "xxthqf": true,
                    "XIHhCb": true,
                    "UsVc8e": false,
                    "HIMA4e": false,
                    "YjL9Ce": false,
                    "wsRfI": false,
                    "UZoA2e": false,
                    "q49bvd": false,
                    "m2hzy": false,
                    "fTZUNc": false,
                    "YrTYaf": true,
                    "WvdhF": false,
                    "Rojixc": "#609beb",
                    "QOuvIc": "#8ab4f8",
                    "hhsybf": false,
                    "Zxl9ce": false,
                    "OL2x3c": false,
                    "Zun3Ef": false,
                    "SOm4o": false,
                    "lL47Xc": false,
                    "l4Npee": false,
                    "tyCgpc": "#202124",
                    "H7aRye": "0px 5px 26px 0px rgba(0,0,0,0.5), 0px 20px 28px 0px rgba(0,0,0,0.5)",
                    "U6xP0": "#4285f4",
                    "A5tF3b": false,
                    "j0DpSe": false,
                    "GUwCvc": false,
                    "ilb27b": "#8ab4f8",
                    "jfyszc": "#8ab4f8",
                    "MpqkGd": "#e8eaed",
                    "NXDvtf": false,
                    "Lxmjn": true,
                    "FydCC": true,
                    "ywhzh": false,
                    "EgTnfe": true,
                    "kAUP3b": false,
                    "hgWJ8c": false,
                    "TxsTcf": "#fff",
                    "v4iQCe": "#4487f6",
                    "OfqeOe": "#2f5eab",
                    "zRpUk": "#6283ff",
                    "QbZklb": "#394457",
                    "Fcb4A": "#8ab4f8",
                    "VRtZRe": "#8ab4f8",
                    "OmYlge": "#219540",
                    "y8HGgf": "#41b85f",
                    "QDXUyc": "#81c995",
                    "JQWqub": "#ff7d70",
                    "nRwuZd": "#f28b82",
                    "rzzybc": "#f28b82",
                    "rZLJJb": "#202124",
                    "hcLEtc": "#0d5432",
                    "GJQmmf": "#1aa863",
                    "hETIfb": "#3c4043",
                    "NtNjtd": "#3c4043",
                    "vCsrw": "#3c4043",
                    "p9416c": "#050607",
                    "toQ7tf": "#0b0d0e",
                    "xgY1nc": "#050505",
                    "p1ocJb": "#0a0a0a",
                    "FCLfBe": "#111",
                    "MnC2zf": "#9aa0a6",
                    "IfdAAd": "#9aa0a6",
                    "fP2Yo": "#9aa0a6",
                    "mknyu": "#9aa0a6",
                    "PUenT": "#bdc1c6",
                    "Z0DEKf": "#bdc1c6",
                    "oHHKwf": "#bdc1c6",
                    "xNPzic": "#202124",
                    "KkPbyc": "#8a4a00",
                    "uezre": "#824300",
                    "SkGiZd": "#b85100",
                    "OxPRr": "#3c4043",
                    "uiKEV": "#e8eaed",
                    "bhxjsd": false,
                    "Co7tHc": true,
                    "qcvoqe": false,
                    "BPltf": "#3c4043",
                    "kcrUme": 14,
                    "m8l8td": "CARET",
                    "zHsZtb": "#dadce0",
                    "zeWvtf": false,
                    "qdoinb": "#9aa0a6",
                    "a4qLne": "#ff7a8e",
                    "RifN2d": "#bdc1c6",
                    "Fpi7Rc": "arial,sans-serif-medium,sans-serif",
                    "a2ykac": "arial,sans-serif",
                    "ME4NMc": "#bdc1c6",
                    "BpPAcd": "#292e36",
                    "N0wyZ": "#bdc1c6",
                    "jxZxne": "#868b90",
                    "CQvMbe": "#48a1ff",
                    "fRkoq": true,
                    "c4qycc": true,
                    "MWZX1c": 20,
                    "IBWrx": 18,
                    "N98mef": false,
                    "WkjuOe": false,
                    "mIjP6d": false,
                    "uJ8Xid": false,
                    "cWwp7b": false,
                    "h6eQZc": false,
                    "b0Jode": false,
                    "mo8CW": true,
                    "CAM7Vc": false,
                    "MomrM": false,
                    "Vb9YJ": true,
                    "OQZvxe": "1px 1px 15px 0px #171717",
                    "fI0P7e": true,
                    "Asoj0e": false,
                    "AP8pqf": "#3c4043",
                    "sBpVac": "rgba(255,255,255,.26)",
                    "JcUGee": "#9aa0a6",
                    "PngPbb": "#bdc1c6",
                    "ENmP1c": "rgba(204,204,204,.15)",
                    "I69zkb": "rgba(204,204,204,.25)",
                    "ib0wve": "rgba(102,102,102,.2)",
                    "a8Umdd": "rgba(102,102,102,.4)",
                    "LVoecd": "rgba(255,255,255,.16)",
                    "yHlFbb": "rgba(255,255,255,.4)",
                    "seVajd": "rgba(255,255,255,.12)",
                    "esUgv": "#fff",
                    "KVmtZc": "rgba(0,0,0,.3)",
                    "MoAfyf": "#000",
                    "ALMSwe": "Roboto,RobotoDraft,Helvetica,Arial,sans-serif",
                    "Sgnmlc": "14px",
                    "qkXvHd": "500",
                    "SezQgf": "500",
                    "EJG4vf": "pointer",
                    "WyvaRd": "0 1px 1px rgba(0,0,0,.16)",
                    "ROAn0e": "0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12)",
                    "rgHLF": true,
                    "KzjxBb": false,
                    "NQ4wzb": false,
                    "TLsp9d": false,
                    "S3hspc": true,
                    "RxFwtc": "1px 1px 15px 0px #171717",
                    "aM8S7c": "#dadce0",
                    "Tae7A": true,
                    "c5h25": true,
                    "MCowFd": false,
                    "LACYrf": false,
                    "uZLNF": true,
                    "wku5sd": false,
                    "JdPOaf": false,
                    "zBxT5": true,
                    "bDOvJc": false,
                    "HCImye": false,
                    "ZMIIMe": true,
                    "B0husb": true,
                    "o28sBd": false,
                    "n4eEIc": true,
                    "tqmosb": "#202124",
                    "HjM8R": "#303134",
                    "ruFjfe": false,
                    "FqP1Fc": "#000",
                    "SATNMc": "1px solid #3c4043",
                    "V0Bluc": "none",
                    "X1bUEc": "arial,sans-serif-medium,sans-serif",
                    "QZheGe": "Google Sans,arial,sans-serif-medium,sans-serif",
                    "LIYDac": "arial,sans-serif",
                    "mNmrAb": "#3c4043",
                    "x0VCkc": "1px solid #3c4043",
                    "Rvxsx": "1px solid #5f6368",
                    "qmcJmd": 6,
                    "JuqxTb": "#bdc1c6",
                    "E6Gkjd": "0 2px 10px 0 rgba(0,0,0,0.2)",
                    "MClBOe": "rgba(255,255,255,0.1)",
                    "V6eh7c": 16,
                    "ZxI7Af": "#3c4043",
                    "sKPNrc": "#3c4043",
                    "AgJzQ": "rgba(255,255,255,0)",
                    "FagChc": "#303134",
                    "tCGJz": "#3c4043",
                    "oqx7yb": "#9aa0a6",
                    "khoEPb": "#8ab4f8",
                    "SfSmD": "#3c4043",
                    "auaxA": "#bdc1c6",
                    "qtDmFc": "rgba(255,255,255,0)",
                    "v44rSc": "#9aa0a6",
                    "YkyDVb": false,
                    "s6k9tc": true,
                    "tdC6kd": true,
                    "fhD9ff": false,
                    "avBLic": false,
                    "UjGOq": false,
                    "sib8M": true,
                    "PGBLg": false,
                    "pWkoAb": false,
                    "IUj4Ye": true,
                    "KYi16e": false,
                    "wUvFOb": false,
                    "a1lsHe": true,
                    "z8cfje": false,
                    "kBxgab": true,
                    "aMqn0b": true,
                    "lHLMtb": false,
                    "Erzlz": false,
                    "KQw3Q": false,
                    "OQFPef": false,
                    "m19P4e": false,
                    "P6Ur2b": "#8ab4f8",
                    "uhXPIc": "#1a73e8",
                    "e127Sb": "#d2e3fc",
                    "ezFdNd": "#81c995",
                    "Wja4f": "#34a853",
                    "jjajId": "#5f6368",
                    "d1ULv": "#3c4043",
                    "lQ1kYd": "#3c4043",
                    "fAus6": "#303134",
                    "NNBneb": "#9aa0a6",
                    "MDi8Rd": "#5f6368",
                    "BoJtxf": false,
                    "ZTuJNc": false,
                    "So4wae": false,
                    "XgWQKd": true,
                    "fjc61": false,
                    "y1HZEd": false,
                    "zAKfhf": false,
                    "D8A8he": true,
                    "bmQ7Rb": false,
                    "nMRhJe": false,
                    "xT28q": false,
                    "KTkDB": false,
                    "JyBo2c": false,
                    "xDKXr": false,
                    "FYBlgf": false,
                    "FELoce": false,
                    "HpkQdc": true,
                    "wwQMXe": false,
                    "FuMeW": true,
                    "bcz7kc": true,
                    "hVG5ce": true,
                    "KCmv6e": false,
                    "IAtx5d": false,
                    "PIZdId": false,
                    "VXIo7d": "8px",
                    "EiEfXb": "#3c4043",
                    "IFkMhd": false,
                    "lsK6rd": true,
                    "zhkRO": "%.@.1,1,1,1,1,1,0,0,null,1,null,0,0,null,0,1,0,\"/setprefs?sig\\u003d0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D\\u0026szl\\u003d0\"]",
                    "w2btAe": "%.@.\"100851705259503639002\",\"100851705259503639002\",\"0\",null,null,null,1]",
                    "pxO4Zd": "0",
                    "mXOY5d": "%.@.null,1,1,null,[null,701,1364]]",
                    "SsQ4x": "x9iHkhRHZETt-9nytNuh5g",
                    "IYFWl": "%.@.\"#424548\"]",
                    "Ht1O2b": "%.@.0]",
                    "d6J1ld": "%.@.0]",
                    "Oo3dKf": "%.@.\"0px 5px 26px 0px rgba(0,0,0,0.5),0px 20px 28px 0px rgba(0,0,0,0.5)\",\"#202124\"]",
                    "uUBnEb": "%.@.\"#ebeced\",\"#303134\",\"#dadce0\",\"#fff\",\"#202124\",\"#dadce0\",\"#dadce0\",\"#9aa0a6\",\"#fff\",\"#fff\",\"#202124\",\"#dadce0\",\"#ea4335\",\"#34a853\",\"#202124\",\"#fff\",\"#fff\",\"#202124\",\"#202124\",\"#3c4043\",\"#5e5e5e\",\"#474747\",\"#f6f6f6\",\"#5f6368\",\"#fff\",\"#23232a\",\"#302322\",\"#2f3039\",\"#3d2c2b\"]",
                    "nfxEDe": "%.@.[],0,null,1,1]",
                    "auIt8": "%.@.0,1]",
                    "YPqjbf": "%.@.\"#bdc1c6\",\"#202124\",\"1px 1px 15px 0px #171717\",\"1px solid #5f6368\",\"#9aa0a6\"]",
                    "MuJWjd": false,
                    "GWsdKe": "vi-VN",
                    "frJqAd": "%.@.\"13px\",\"16px\",\"11px\",13,16,11,\"8px\",8,20]",
                    "N1ycab": "vi_VN",
                    "AB5Xwb": "%.@.\"10px\",10,\"16px\",16,\"18px\"]",
                    "Z8HLFf": "%.@.\"14px\",14]",
                    "ymaOI": "%.@.40,32,14,\"\\\"#dadce0\\\"\"]",
                    "fNpQmb": "%.@.\"Roboto-Bold,HelveticaNeue-Bold,HelveticaNeue,sans-serif-bold,Arial,sans-serif\"]",
                    "aMI2mb": "%.@.\"1px 1px 15px 0px #171717\"]",
                    "BZUDzc": "%.@.0,\"14px\",\"500\",\"500\",\"0 1px 1px rgba(0,0,0,.16)\",\"pointer\",\"#fff\",\"rgba(255,255,255,.26)\",\"#9aa0a6\",\"#bdc1c6\",\"rgba(204,204,204,.15)\",\"rgba(204,204,204,.25)\",\"rgba(102,102,102,.2)\",\"rgba(102,102,102,.4)\",\"#1aa863\",\"#4487f6\",\"#8ab4f8\",\"#ff7d70\",\"#8a4a00\",\"#111\",\"#050505\",\"#bdc1c6\",\"#4f861f\",\"rgba(255,255,255,.12)\",null,\"#202124\",\"rgba(0,0,0,.3)\",\"#000\",\"#bdc1c6\",\"#000\",null,1]",
                    "v7Qvdc": "%.@.\"20px\",\"500\",\"400\",\"13px\",\"15px\",\"15px\",\"Roboto,RobotoDraft,Helvetica,Arial,sans-serif\",\"24px\",\"400\",\"32px\",\"24px\"]",
                    "MgUcDb": "VN",
                    "SIsrTd": false,
                    "fyLpDc": "",
                    "ZxtPCd": "%.@.null,null,null,null,20,null,18,\"44px\",null,\"36px\",null,null,null,null,null,null,null,null,null,null,\"#202124\",null,null,null,null,null,null,null,null,\"16px\",\"12px\",\"8px\",null,null,\"rgba(138,180,248,0.24)\",\"#d2e3fc\",\"transparent\",\"#8ab4f8\",\"#5f6368\",\"9999px\",\"8px\",\"#d2e3fc\",\"transparent\",\"#dadce0\",\"#5f6368\",null,null,null,null,null,\"Google Sans,arial,sans-serif-medium,sans-serif\",\"20px\",\"14px\",\"500\",\"#3c4043\",\"#e8eaed\",\"#202124\",\"#5f6368\",\"#dadce0\",null,\"#d2e3fc\",\"#d2e3fc\",null,null,null,null,null,null,null,null,null,null,\"#8ab4f8\",\"2px\",null,null,\"rgba(138,180,248,0.24)\",null,null,null,null,\"34px\",null,\"7px\",\"1px\",null,null,null,null,null,null,\"rgba(138,180,248,0.24)\",\"rgba(138,180,248,0.24)\",null,\"#8ab4f8\",null,\"#34517d\",\"#eef0ff\",16,{\"100\":\"12px\",\"101\":\"8px\",\"102\":\"8px\",\"103\":\"10px\"}]",
                    "NyzCwe": "%.@.\"#9aa0a6\",\"#9aa0a6\",\"#9aa0a6\",\"#9aa0a6\",\"#bdc1c6\",\"#e8eaed\",\"8px\",\"100%\",\"12px\",\"0px\",\"8px\",\"8px\",\"4px\",\"100%\",\"6px\",\"8px\",\"0px\",\"16px\",null,\"#c3c6d6\",\"#e8e8e8\",null,\"#9e9e9e\"]",
                    "spz2q": "%.@.\"#202124\",\"0px\",null,\"0px\",null,\"0px\"]",
                    "xFmcof": "%.@.\"100%\",\"4px\",\"0px\",\"20px\",\"12px\"]",
                    "lDqiof": "%.@.\"#e8eaed\",\"#bdc1c6\",\"#8ab4f8\",null,\"#9aa0a6\",\"#8ab4f8\",\"#c58af9\",null,null,\"#202124\",\"#8ab4f8\",\"#202124\",\"#394457\",\"#d2e3fc\",\"#303134\",\"#bdc1c6\",\"#fff\",\"#3c4043\",\"#202124\",\"#fff\",\"#202124\",\"#fff\",\"#81c995\",\"#f28b82\",\"#fdd663\",\"#3c4043\",\"#202124\",\"rgba(0,0,0,0.6)\",\"#bdc1c6\",\"#3c4043\",\"#8ab4f8\",null,\"#8ab4f8\",\"#9aa0a6\",null,\"transparent\",\"#3c4043\",\"rgba(0,0,0,0.03)\",null,null,null,null,null,null,null,null,null,\"#ea4335\",\"#34a853\",\"#4285f4\",\"#fbbc04\",\"#fdd663\",\"#80868b\",\"#171717\",null,null,null,null,\"#394457\",\"#28292a\",\"#333438\",\"rgba(232,234,237,0.5)\",\"#444746\",\"#3c4665\",\"#f2b8b5\",\"#8c1d18\",\"#f4bf00\",\"#ffdf92\",\"#601410\",\"#f9dedc\",\"#241a00\",\"#241a00\",\"#0a3818\",\"#c4eed0\",\"#f2b8b5\",\"#6dd58c\",\"#6dd58c\",\"#c4eed0\",\"#757fa4\",\"#757fa4\",\"#757fa4\",\"#424654\",\"#5c5f5e\",\"#333438\",\"#303134\",\"#eef0ff\"]",
                    "Gpnz4c": "%.@.\"#3c4665\",\"#2d2f31\",\"#444746\",\"#b1c5ff\",\"#c3c6d6\",\"#eef0ff\",\"#2d2f31\",\"#2c303d\",\"#eef0ff\",\"#3a3f50\",\"#202124\",\"#9e9e9e\",\"#bfbfbf\",\"#e8e8e8\",\"#a6c9fc\",\"#444746\",\"#a8c7fa\",\"#a8c7fa\",\"#34517d\",\"#eef0ff\",\"#333438\",\"#28292a\",\"#1f1f1f\",\"#202124\",\"#303134\",\"#3c4665\",\"#f5f8ff\",\"#424654\",\"#424654\",\"#1f1f1f\",\"#242832\",\"#b1c5ff\",\"#c3c6d6\",\"#eef0ff\",\"#2c303d\",\"#2c303d\",\"#eef0ff\",\"#3a3f50\",\"#202124\",\"#fff\",\"#c3c6d6\",\"#eef0ff\",\"#eef0ff\",\"#b1c5ff\",\"#424654\",\"#a8c7fa\",\"#a8c7fa\",\"rgba(0,0,0,0.6)\",\"#34517d\",\"#eef0ff\",\"#1f1f1f\",\"#242832\",\"#3a3f50\",\"#333438\"]",
                    "sCU50d": "%.@.null,\"none\",null,\"0px 1px 3px rgba(23,23,23,0.24)\",null,\"0px 2px 6px rgba(23,23,23,0.32)\",null,\"0px 4px 12px rgba(23,23,23,0.9)\",null,null,\"1px solid #5f6368\",\"none\",\"none\",\"none\",\"none\",\"0px 1px 3px rgba(95,99,104,0.64)\"]",
                    "w9Zicc": "%.@.\"#fff\",\"26px\",\"#fff\",\"#697988\",\"#fff\",\"1px\",\"#9aa0a6\",\"1px\",\"#fff\",\"#9aa0a6\",\"#e2eeff\",\"12px\",\"12px\",\"10px\",\"16px\",\"16px\",\"20px\",\"12px\",\"10px\",\"8px\",\"#2a4165\",\"#fff\",\"#fff\"]",
                    "IkSsrf": "%.@.\"Google Sans,arial,sans-serif\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"arial,sans-serif\",\"arial,sans-serif-medium,sans-serif\",\"arial,sans-serif-light,sans-serif\"]",
                    "OItNqf": "%.@.\"1px\",\"20\",\"20px\",\"14px\"]",
                    "JMyuH": "%.@.null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,\"36px\",\"20px\"]",
                    "j2FoS": "%.@.\"#c3c6d6\",\"#28292a\",\"#e8e8e8\",\"#e8e8e8\",\"#9e9e9e\",\"#e8e8e8\",\"500\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"20px\",\"16px\",\"83px\",\"92px\",\"52px\",\"52px\",\"#9e9e9e\"]",
                    "e2zoW": "%.@.\"16px\",\"12px\",\"0px\",\"8px\",\"4px\",\"2px\",\"20px\",\"24px\",\"48px\",\"20px 20px\",null,null,\"0px\",\"20px\",\"36px\",\"20px\"]",
                    "W1Bte": "%.@.\"cubic-bezier(0.1,1,0.2,1)\",\"cubic-bezier(0.8,0,1,0.8)\",\"cubic-bezier(0.2,0.6,0.2,1)\",\"cubic-bezier(0.4,0,1,0.8)\",\"300\",\"100ms\",\"200ms\",\"250ms\",\"cubic-bezier(0.4,0,0.2,1)\",\"cubic-bezier(0.4,0,0.6,1)\",\"cubic-bezier(0.6,0,0,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"800ms\",\"1000ms\",\"400ms\",\"500ms\",\"600ms\",\"50ms\",\"400ms\",\"300ms\",\"250ms\",\"150ms\",\"250ms\",\"200ms\",\"150ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"150ms\",\"450ms\",\"400ms\",\"300ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"null\",\"cubic-bezier(0.3,0,0.8,0.15)\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"cubic-bezier(0.3,0,1,1)\",\"cubic-bezier(0,0,0,1)\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"400ms\",\"350ms\",\"250ms\",\"50ms\",\"50ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"50ms\",\"50ms\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0.3,0,0.8,0.15)\"]",
                    "u9mep": "%.@.\"#8ab4f8\",\"#8ab4f8\",\"#e8e8e8\",\"#8ab4f8\"]",
                    "mrqaQb": "%.@.14,6,68,\"#bfbfbf\",2,12]",
                    "k7Tqye": "%.@.null,null,null,null,null,null,null,\"16px\",\"12px\",\"8px\",\"20px\",\"4px\",\"9999px\",\"0px\",\"2px\"]",
                    "y50LC": "%.@.null,null,\"#bdc1c6\",null,\"#bcc0c3\"]",
                    "jfSEkd": "%.@.\"#a8c7fa\",\"#34517d\",\"#eef0ff\",\"#eef0ff\",\"rgba(255,255,255,0.08)\",\"rgba(255,255,255,0.08)\",\"rgba(255,255,255,0.24)\",\"#bfbfbf\",\"#444746\",\"#444746\",\"#28292a\",\"#a8c7fa\",\"#202124\",\"rgba(255,255,255,0.16)\",\"rgba(255,255,255,0.16)\",\"rgba(255,255,255,0.4)\",\"#2c303d\",\"#eef0ff\",\"rgba(189,193,198,0.08)\",\"rgba(189,193,198,0.08)\",\"rgba(189,193,198,0.24)\",\"transparent\",\"#8ab4f8\",\"#8ab4f8\",\"rgba(138,180,248,0.08)\",\"rgba(138,180,248,0.08)\",\"rgba(138,180,248,0.24)\",\"transparent\",\"#9e9e9e\",\"#bdc1c6\",\"rgba(189,193,198,0.08)\",\"rgba(189,193,198,0.08)\",\"rgba(189,193,198,0.24)\",\"2px\",\"2px\",null,null,\"#2c303d\",null,\"#b1c5ff\",\"#28292a\",\"#e8e8e8\",\"#c3c6d6\",\"#e8e8e8\",\"#e8e8e8\",\"15\",\"15\",\"39\"]",
                    "GVtPm": "%.@.\"#202124\",null,null,null,\"8px\",\"0 0 0 1px #3c4043\",\"1px solid #3c4043\",\"#1f1f1f\",\"#28292a\",\"#333438\",\"#9e9e9e\",\"#bfbfbf\",\"26vw\",\"40vw\",\"55vw\"]",
                    "MexNte": "%.@.\"700\",\"400\",\"underline\",\"none\",\"capitalize\",\"none\",\"uppercase\",\"none\",\"500\",\"lowercase\",\"italic\",null,null,\"-1px\",\"0.3px\",\"20px\",\"12px\",\"var(--google-fs,1)\"]",
                    "Aahcnf": "%.@.\"28px\",\"36px\",\"400\",\"Google Sans,arial,sans-serif\",null,\"arial,sans-serif\",\"14px\",\"400\",\"22px\",null,\"18px\",\"24px\",\"400\",\"Google Sans,arial,sans-serif\",null,\"Google Sans,arial,sans-serif\",\"56px\",\"48px\",\"0\",null,\"400\",\"Google Sans,arial,sans-serif\",\"36px\",\"400\",\"40px\",null,\"Google Sans,arial,sans-serif\",\"36px\",\"28px\",null,\"400\",null,\"arial,sans-serif\",\"24px\",\"18px\",null,\"400\",\"arial,sans-serif\",\"16px\",\"12px\",null,\"400\",\"arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"arial,sans-serif\",\"24px\",\"20px\",null,\"400\",\"arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"arial,sans-serif\",\"18px\",\"14px\",null,\"400\",null,null,null,null,null,\"14px\",\"Google Sans,arial,sans-serif\",\"20px\",\"400\",\"Google Sans,arial,sans-serif\",\"28px\",\"22px\",\"400\",\"Google Sans,arial,sans-serif\",\"24px\",\"16px\",\"400\",\"arial,sans-serif-medium,sans-serif\",\"16px\",\"12px\",\"Google Sans,arial,sans-serif\",\"28px\",\"22px\",\"400\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"16px\",\"12px\",\"500\"]",
                    "PFhmed": "%.@.\"rgba(32,33,36,0)\",\"rgba(32,33,36,0.9)\",\"#9aa0a6\"]",
                    "RsSoV": "%.@.\"rgba(1,1,1,0.25)\",\"rgba(0,0,0,0)\",\"0.87\",\"3px\",14,\"10px\",\"16px\",\"2px\",\"8px\",\"2px\",\"16px\",\"12px\",\"#d93025\",\"8px\",\"12px\",\"rgba(255,255,255,0.25)\",\"4px\",\"7px\",\"500\",\"rgba(255,255,255,0.85)\"]",
                    "mf1yif": "%.@.4]",
                    "B4pZbd": "VN",
                    "aKXqGc": "%.@.\"14px\",14,\"16px\",16,\"0\",0,\"none\",652,\"1px solid #3c4043\",\"normal\",\"normal\",\"#9aa0a6\",\"12px\",\"1.34\",\"1px solid #3c4043\",\"none\",\"0\",\"none\",\"none\",\"none\",\"none\",\"6px\",\"652px\"]",
                    "ZP0oif": "%.@.\"16px\",\"#303134\"]",
                    "o0P8Hf": "%.@.\"rgba(255,255,255,.0)\",null,null,null,\"#dddee1\",\"#212327\",null,null,null,\"#303134\",\"#fff\",\"#48a1ff\",\"#212327\",\"#000\",\"#000\",null,\"#868b90\",\"rgba(255,255,255,.26)\",\"rgba(255,255,255,.2)\",\"rgba(255,255,255,.5)\",\"rgba(255,255,255,.2)\",\"#000\",\"rgba(0,0,0,.1)\",\"#fff\",\"#70757a\",null,\"#fff\",\"#000\",\"#fff\",\"rgba(255,255,255,.0)\",\"rgba(255,255,255,.5)\",\"rgba(255,255,255,.03)\",\"rgba(0,0,0,.3)\",\"rgba(0,0,0,.2)\",\"rgba(0,0,0,.5)\",\"rgba(255,255,255,.07)\",\"rgba(0,0,0,.04)\",\"rgba(255,255,255,.26)\",\"rgba(0,0,0,.54)\",\"#868b90\",\"#868b90\",\"rgba(0,0,0,.22)\",\"rgba(0,0,0,.30)\",\"rgba(0,0,0,.06)\",\"rgba(255,255,255,.25)\",\"#0f2039\",\"rgba(221,222,225,.5)\",\"rgba(221,222,225,.7)\",\"rgba(255,255,255,.04)\",null,null,\"rgba(255,255,255,.8)\",\"rgba(60,64,67,.15)\",\"rgba(0,0,0,.07)\",\"rgba(0,0,0,.16)\",\"rgba(0,0,0,.08)\",\"rgba(0,0,0,.14)\",\"rgba(0,0,0,.12)\",\"rgba(0,0,0,.28)\",\"rgba(0,0,0,.18)\",\"rgba(0,0,0,.24)\",\"rgba(0,0,0,.05)\",\"rgba(0,0,0,.13)\",\"rgba(60,64,67,.3)\",\"rgba(0,0,0,.36)\",\"rgba(0,0,0,.15)\",\"rgba(32,33,36,.28)\",\"rgba(218,220,224,.7)\",\"#dadce0\",\"#fff\",\"#fff\",\"#1a73e8\",\"#000\",\"rgba(0,0,0,.0)\",\"#202124\",\"rgba(0,0,0,.8)\",\"rgba(26,115,232,.0)\",\"rgba(26,115,232,.7)\",\"rgba(66,133,244,.22)\",\"rgba(32,33,36,.7)\",\"rgba(255,255,255,.8)\",\"rgba(0,0,0,.54)\",\"rgba(0,0,0,.87)\",\"rgba(188,192,195,.38)\",\"rgba(0,0,0,.8)\",\"rgba(255,255,255,.54)\",\"rgba(255,255,255,.87)\",\"rgba(60,64,67,.38)\",\"rgba(255,255,255,.3)\",\"rgba(0,0,0,0.54)\",\"rgba(0,0,0,0.8)\",\"rgba(248,249,250,0.85)\",\"#212327\",\"#ff7769\",\"#219540\",\"#bcc0c3\",\"#050607\",\"#bcc0c3\",\"#dddee1\",{\"100\":\"#050607\",\"101\":\"#212327\",\"102\":\"#bcc0c3\",\"103\":\"#dddee1\",\"104\":\"#050607\",\"105\":\"#212327\",\"106\":\"#868b90\",\"107\":\"#bcc0c3\",\"108\":\"#050607\",\"109\":\"#bcc0c3\",\"110\":\"#dddee1\",\"111\":\"#f8f9fa\",\"112\":\"#dadce0\",\"113\":\"#08101e\",\"114\":\"#4487f6\",\"115\":\"#08101e\",\"116\":\"#0f2039\",\"117\":\"#4487f6\",\"118\":\"#48a1ff\",\"119\":\"#08101e\",\"120\":\"#0f2039\",\"121\":\"#4487f6\",\"122\":\"#48a1ff\",\"123\":\"#0f2039\",\"124\":\"#4487f6\",\"125\":\"#48a1ff\",\"126\":\"#08101e\",\"127\":\"#0f2039\",\"128\":\"#4487f6\",\"129\":\"#48a1ff\",\"130\":\"#230f0d\",\"131\":\"#441c19\",\"132\":\"#b04940\",\"133\":\"#e76055\",\"134\":\"#ff897e\",\"135\":\"#ff9895\",\"136\":\"#ffb1b1\",\"137\":\"#ff7769\",\"138\":\"#ff897e\",\"139\":\"#ff7769\",\"140\":\"#ff897e\",\"141\":\"#ff9895\",\"142\":\"#ffa8a6\",\"143\":\"#ffb1b1\",\"144\":\"#ff897e\",\"145\":\"#b04940\",\"146\":\"#e76055\",\"147\":\"#ff7769\",\"148\":\"#ff9895\",\"149\":\"#ffb1b1\",\"150\":\"#0f0800\",\"151\":\"#1f1000\",\"152\":\"#381d00\",\"153\":\"#502900\",\"154\":\"#693600\",\"155\":\"#824300\",\"156\":\"#994b00\",\"157\":\"#af5600\",\"158\":\"#c66200\",\"159\":\"#db6c00\",\"160\":\"#824300\",\"161\":\"#824300\",\"162\":\"#af5600\",\"163\":\"#502900\",\"164\":\"#824300\",\"165\":\"#693600\",\"166\":\"#824300\",\"167\":\"#994b00\",\"168\":\"#af5600\",\"169\":\"#c66200\",\"170\":\"#db6c00\",\"171\":\"#041208\",\"172\":\"#082410\",\"173\":\"#0e401b\",\"174\":\"#145c28\",\"175\":\"#1a7833\",\"176\":\"#3cac5c\",\"177\":\"#4eb66e\",\"178\":\"#219540\",\"179\":\"#3cac5c\",\"180\":\"#4eb66e\",\"181\":\"#219540\",\"182\":\"#3cac5c\",\"183\":\"#082410\",\"184\":\"#0e401b\",\"185\":\"#219540\",\"186\":\"#145c28\",\"187\":\"#219540\",\"188\":\"#3cac5c\",\"189\":\"#4eb66e\",\"190\":\"#5ebe7e\",\"191\":\"#70c890\",\"192\":\"rgba(255,255,255,.1)\",\"193\":\"rgba(255,255,255,.2)\",\"194\":\"rgba(60,64,67,.10)\",\"195\":\"rgba(60,64,67,.06)\",\"196\":\"rgba(0,0,0,.0)\",\"197\":\"rgba(255,255,255,.12)\",\"198\":\"rgba(32,33,36,.0)\",\"199\":\"rgba(32,33,36,.1)\",\"200\":\"rgba(255,255,255,.12)\",\"201\":\"rgba(255,255,255,.5)\",\"202\":\"rgba(255,255,255,.54)\",\"203\":\"#fff\",\"204\":\"rgba(0,0,0,.5)\",\"205\":\"#6eb1ff\",\"206\":\"rgba(255,255,255,.24)\",\"207\":\"rgba(0,0,0,.24)\",\"208\":\"#f8f9fa\",\"209\":\"rgba(255,255,255,.6)\",\"210\":\"#1e8e3e\",\"211\":\"rgba(0,0,0,.02)\",\"212\":\"#000\",\"213\":\"rgba(255,255,255,.16)\",\"214\":\"rgba(0,0,0,.7)\",\"215\":\"#1a73e8\",\"216\":\"#d93025\",\"217\":\"#4285f4\",\"218\":\"rgba(255,255,255,.15)\",\"219\":\"rgba(255,255,255,.05)\",\"220\":\"#70757a\",\"221\":\"#dadce0\",\"222\":\"#188038\",\"223\":\"rgba(0,0,0,.6)\",\"224\":\"#34a853\",\"225\":\"rgba(255,255,255,.3)\",\"226\":\"rgba(0,0,0,.05)\",\"227\":\"rgba(0,0,0,.05)\",\"228\":\"rgba(32,33,36,.9)\",\"229\":\"rgba(0,0,0,.6)\",\"230\":\"rgba(255,255,255,.08)\",\"231\":\"rgba(0,0,0,.8)\",\"232\":\"rgba(255,255,255,.05)\",\"233\":\"#4285f4\",\"234\":\"rgba(255,255,255,.16)\",\"235\":\"#000\",\"236\":\"rgba(0,0,0,.87)\",\"238\":\"#fdd663\",\"239\":\"#fdd663\",\"240\":\"#fff\",\"241\":\"rgba(255,255,255,.5)\",\"242\":\"#f8f9fa\",\"243\":\"#fdd663\",\"244\":\"rgba(255,255,255,.54)\",\"245\":\"rgba(0,0,0,.5)\",\"246\":\"rgba(0,0,0,.26)\",\"247\":\"rgba(0,0,0,.26)\",\"248\":\"rgba(0,0,0,.38)\",\"249\":\"rgba(0,0,0,.03)\",\"250\":\"#4285f4\",\"251\":\"rgba(60,64,67,.12)\",\"252\":\"rgba(255,255,255,.0)\",\"253\":\"rgba(0,0,0,.0)\",\"254\":\"#3c4043\",\"255\":\"#d2e3fc\",\"256\":\"#3c4043\",\"257\":\"#d2e3fc\",\"258\":\"#d2e3fc\",\"259\":\"#4285f4\",\"260\":\"#202124\",\"261\":\"rgba(0,0,0,.16)\",\"262\":\"rgba(255,255,255,.3)\",\"263\":\"rgba(255,255,255,.0)\",\"264\":\"#c5221f\",\"265\":\"#dadce0\",\"266\":\"#ea4335\",\"267\":\"#34a853\",\"268\":\"rgba(188,192,195,.15)\",\"269\":\"rgba(94,190,126,.15)\",\"270\":\"rgba(255,255,255,.15)\",\"271\":\"rgba(255,255,255,.18)\",\"272\":\"rgba(255,255,255,.28)\",\"273\":\"rgba(188,192,195,.3)\",\"274\":\"#1558d6\"}]",
                    "rkD25": "%.@.[[\"hl\",\"vi-VN\"]]]",
                    "WiLzZe": "%.@.\"#dddee1\",\"#868b90\",\"#bdc1c6\",\"#bcc0c3\",\"#000\",\"rgba(0,0,0,.7)\",28,24,26,20,16,-2,0,-4,2,0,0,24,20,20,14,12]",
                    "AYkLRe": "%.@.\"20px\",20,\"14px\",14,\"#e8eaed\"]",
                    "rNyuJc": "ngockhoannk@gmail.com",
                    "LU5fGb": true,
                    "gXkHoe": "100851705259503639002",
                    "hevonc": "%.@.1]",
                    "xcljyb": "%.@.\"8px\",8,\"Roboto-Medium,HelveticaNeue-Medium,Helvetica Neue,sans-serif-medium,Arial,sans-serif\"]"
                };
            }
            )();
            (function() {
                var b = function(a) {
                    var c = 0;
                    return function() {
                        return c < a.length ? {
                            done: !1,
                            value: a[c++]
                        } : {
                            done: !0
                        }
                    }
                };
                var e = this || self;
                var g, h;
                a: {
                    for (var k = ["CLOSURE_FLAGS"], l = e, n = 0; n < k.length; n++)
                        if (l = l[k[n]],
                        null == l) {
                            h = null;
                            break a
                        }
                    h = l
                }
                var p = h && h[610401301];
                g = null != p ? p : !1;
                var q, r = e.navigator;
                q = r ? r.userAgentData || null : null;
                function t(a) {
                    return g ? q ? q.brands.some(function(c) {
                        return (c = c.brand) && -1 != c.indexOf(a)
                    }) : !1 : !1
                }
                function u(a) {
                    var c;
                    a: {
                        if (c = e.navigator)
                            if (c = c.userAgent)
                                break a;
                        c = ""
                    }
                    return -1 != c.indexOf(a)
                }
                ;function v() {
                    return g ? !!q && 0 < q.brands.length : !1
                }
                function w() {
                    return u("Safari") && !(x() || (v() ? 0 : u("Coast")) || (v() ? 0 : u("Opera")) || (v() ? 0 : u("Edge")) || (v() ? t("Microsoft Edge") : u("Edg/")) || (v() ? t("Opera") : u("OPR")) || u("Firefox") || u("FxiOS") || u("Silk") || u("Android"))
                }
                function x() {
                    return v() ? t("Chromium") : (u("Chrome") || u("CriOS")) && !(v() ? 0 : u("Edge")) || u("Silk")
                }
                function y() {
                    return u("Android") && !(x() || u("Firefox") || u("FxiOS") || (v() ? 0 : u("Opera")) || u("Silk"))
                }
                ;var z = v() ? !1 : u("Trident") || u("MSIE");
                y();
                x();
                w();
                Object.freeze(new function() {}
                );
                Object.freeze(new function() {}
                );
                var A = !z && !w()
                  , D = function(a) {
                    if (/-[a-z]/.test("ved"))
                        return null;
                    if (A && a.dataset) {
                        if (y() && !("ved"in a.dataset))
                            return null;
                        a = a.dataset.ved;
                        return void 0 === a ? null : a
                    }
                    return a.getAttribute("data-" + "ved".replace(/([A-Z])/g, "-$1").toLowerCase())
                };
                var E = []
                  , F = null;
                function G(a) {
                    a = a.target;
                    var c = performance.now()
                      , f = []
                      , H = f.concat
                      , d = E;
                    if (!(d instanceof Array)) {
                        var m = "undefined" != typeof Symbol && Symbol.iterator && d[Symbol.iterator];
                        if (m)
                            d = m.call(d);
                        else if ("number" == typeof d.length)
                            d = {
                                next: b(d)
                            };
                        else
                            throw Error("a`" + String(d));
                        for (var B = []; !(m = d.next()).done; )
                            B.push(m.value);
                        d = B
                    }
                    E = H.call(f, d, [c]);
                    if (a && a instanceof HTMLElement)
                        if (a === F) {
                            if (c = 4 <= E.length)
                                c = 5 > (E[E.length - 1] - E[E.length - 4]) / 1E3;
                            if (c) {
                                c = google.getEI(a);
                                a.hasAttribute("data-ved") ? f = a ? D(a) || "" : "" : f = (f = a.closest("[data-ved]")) ? D(f) || "" : "";
                                f = f || "";
                                if (a.hasAttribute("jsname"))
                                    a = a.getAttribute("jsname");
                                else {
                                    var C;
                                    a = null == (C = a.closest("[jsname]")) ? void 0 : C.getAttribute("jsname")
                                }
                                google.log("rcm", "&ei=" + c + "&ved=" + f + "&jsname=" + (a || ""))
                            }
                        } else
                            F = a,
                            E = [c]
                }
                window.document.addEventListener("DOMContentLoaded", function() {
                    document.body.addEventListener("click", G)
                });
            }
            ).call(this);
            var w = function(a) {
                var b = 0;
                return function() {
                    return b < a.length ? {
                        done: !1,
                        value: a[b++]
                    } : {
                        done: !0
                    }
                }
            };
            window.jsl = window.jsl || {};
            window.jsl.dh = function(a, b, m) {
                try {
                    var h = document.getElementById(a), e;
                    if (!h && (null == (e = google.stvsc) ? 0 : e.dds)) {
                        e = [];
                        var f = e.concat
                          , c = google.stvsc.dds;
                        if (c instanceof Array)
                            var n = c;
                        else {
                            var p = "undefined" != typeof Symbol && Symbol.iterator && c[Symbol.iterator];
                            if (p)
                                var g = p.call(c);
                            else if ("number" == typeof c.length)
                                g = {
                                    next: w(c)
                                };
                            else
                                throw Error(String(c) + " is not an iterable or ArrayLike");
                            c = g;
                            var q;
                            for (g = []; !(q = c.next()).done; )
                                g.push(q.value);
                            n = g
                        }
                        var r = f.call(e, n);
                        for (f = 0; f < r.length && !(h = r[f].getElementById(a)); f++)
                            ;
                    }
                    if (h)
                        h.innerHTML = b,
                        m && m();
                    else {
                        var d = {
                            id: a,
                            script: String(!!m),
                            milestone: String(google.jslm || 0)
                        };
                        google.jsla && (d.async = google.jsla);
                        var t = a.indexOf("_")
                          , k = 0 < t ? a.substring(0, t) : ""
                          , u = document.createElement("div");
                        u.innerHTML = b;
                        var l = u.children[0];
                        if (l && (d.tag = l.tagName,
                        d["class"] = String(l.className || null),
                        d.name = String(l.getAttribute("jsname")),
                        k)) {
                            a = [];
                            var v = document.querySelectorAll('[id^="' + k + '_"]');
                            for (b = 0; b < v.length; ++b)
                                a.push(v[b].id);
                            d.ids = a.join(",")
                        }
                        google.ml(Error(k ? "Missing ID with prefix " + k : "Missing ID"), !1, d)
                    }
                } catch (x) {
                    google.ml(x, !0, {
                        "jsl.dh": !0
                    })
                }
            }
            ;
            (function() {
                var x = true;
                google.jslm = x ? 2 : 1;
            }
            )();
            google.x(null, function() {
                (function() {
                    (function() {
                        google.csct = {};
                        google.csct.ps = 'AOvVaw3F_XpuCmvKJESpO2sjQ2ES\x26ust\x3d1704526554456124';
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        google.csct.rl = true;
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        google.csct.pi = true;
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        function f() {
                            for (var c = "&cshid=" + window._cshid, d = document.querySelectorAll('[href^="/"]'), e = 0, b; b = d[e++]; ) {
                                var a = b.getAttribute("href");
                                a.match(/[\?|&](ei|ved)=/) && -1 === a.indexOf("cshid=") && (-1 === a.search("#") ? b.setAttribute("href", a + c) : (a = a.split("#"),
                                b.setAttribute("href", a[0] + c + "#" + a[1])))
                            }
                            d = document.querySelectorAll("[ping]");
                            for (e = 0; b = d[e++]; )
                                a = b.getAttribute("ping"),
                                -1 === a.indexOf("cshid=") && b.setAttribute("ping", a + c)
                        }
                        ;google.csh = google.csh || {};
                        google.csh.ict = function() {
                            window._cshid && google.dclc(f)
                        }
                        ;
                    }
                    ).call(this);
                }
                )();
                (function() {
                    google.csh.ict();
                }
                )();
                (function() {
                    window.jsl = window.jsl || {};
                    window.jsl.dh = window.jsl.dh || function(i, c, d) {
                        try {
                            var e = document.getElementById(i);
                            if (e) {
                                e.innerHTML = c;
                                if (d) {
                                    d();
                                }
                            } else {
                                if (window.jsl.el) {
                                    window.jsl.el(new Error('Missing ID.'), {
                                        'id': i
                                    });
                                }
                            }
                        } catch (e) {
                            if (window.jsl.el) {
                                window.jsl.el(new Error('jsl.dh'));
                            }
                        }
                    }
                    ;
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_1', '\x3cstyle\x3e.gb_bb:not(.gb_dd){font:13px/27px Roboto,Arial,sans-serif;z-index:986}@-webkit-keyframes gb__a{0%{opacity:0}50%{opacity:1}}@keyframes gb__a{0%{opacity:0}50%{opacity:1}}a.gb_sa{border:none;color:#4285f4;cursor:default;font-weight:bold;outline:none;position:relative;text-align:center;text-decoration:none;text-transform:uppercase;white-space:nowrap;-webkit-user-select:none}a.gb_sa:hover:after,a.gb_sa:focus:after{background-color:rgba(0,0,0,.12);content:\x22\x22;height:100%;left:0;position:absolute;top:0;width:100%}a.gb_sa:hover,a.gb_sa:focus{text-decoration:none}a.gb_sa:active{background-color:rgba(153,153,153,.4);text-decoration:none}a.gb_ta{background-color:#4285f4;color:#fff}a.gb_ta:active{background-color:#0043b2}.gb_ua{box-shadow:0 1px 1px rgba(0,0,0,.16)}.gb_sa,.gb_ta,.gb_va,.gb_wa{display:inline-block;line-height:28px;padding:0 12px;border-radius:2px}.gb_va{background:#f8f8f8;border:1px solid #c6c6c6}.gb_wa{background:#f8f8f8}.gb_va,#gb a.gb_va.gb_va,.gb_wa{color:#666;cursor:default;text-decoration:none}#gb a.gb_wa{cursor:default;text-decoration:none}.gb_wa{border:1px solid #4285f4;font-weight:bold;outline:none;background:#4285f4;background:-webkit-gradient(linear,left top,left bottom,from(top),color-stop(#4387fd),to(#4683ea));background:-webkit-linear-gradient(top,#4387fd,#4683ea);background:linear-gradient(top,#4387fd,#4683ea);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr\x3d#4387fd,endColorstr\x3d#4683ea,GradientType\x3d0)}#gb a.gb_wa{color:#fff}.gb_wa:hover{box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_wa:active{box-shadow:inset 0 2px 0 rgba(0,0,0,.15);background:#3c78dc;background:-webkit-gradient(linear,left top,left bottom,from(top),color-stop(#3c7ae4),to(#3f76d3));background:-webkit-linear-gradient(top,#3c7ae4,#3f76d3);background:linear-gradient(top,#3c7ae4,#3f76d3);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr\x3d#3c7ae4,endColorstr\x3d#3f76d3,GradientType\x3d0)}#gb .gb_xa{background:#fff;border:1px solid #dadce0;color:#1a73e8;display:inline-block;text-decoration:none}#gb .gb_xa:hover{background:#f8fbff;border-color:#dadce0;color:#174ea6}#gb .gb_xa:focus{background:#f4f8ff;color:#174ea6;outline:1px solid #174ea6}#gb .gb_xa:active,#gb .gb_xa:focus:active{background:#ecf3fe;color:#174ea6}#gb .gb_xa.gb_j{background:transparent;border:1px solid #5f6368;color:#8ab4f8;text-decoration:none}#gb .gb_xa.gb_j:hover{background:rgba(255,255,255,.04);color:#e8eaed}#gb .gb_xa.gb_j:focus{background:rgba(232,234,237,.12);color:#e8eaed;outline:1px solid #e8eaed}#gb .gb_xa.gb_j:active,#gb .gb_xa.gb_j:focus:active{background:rgba(232,234,237,.1);color:#e8eaed}.gb_p{display:none!important}.gb_Va{visibility:hidden}.gb_v{display:inline-block;vertical-align:middle}.gb_Md .gb_o{bottom:-3px;right:-5px}.gb_g{position:relative}.gb_d{display:inline-block;outline:none;vertical-align:middle;border-radius:2px;box-sizing:border-box;height:40px;width:40px;cursor:pointer;text-decoration:none}#gb#gb a.gb_d{cursor:pointer;text-decoration:none}.gb_d,a.gb_d{color:#000}.gb_cf{border-color:transparent;border-bottom-color:#fff;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;top:33px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s}.gb_df{border-color:transparent;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s;border-bottom-color:rgba(0,0,0,.2);top:32px}x:-o-prefocus,div.gb_df{border-bottom-color:#ccc}.gb_0{background:#fff;border:1px solid #ccc;border-color:rgba(0,0,0,.2);color:#000;-webkit-box-shadow:0 2px 10px rgba(0,0,0,.2);box-shadow:0 2px 10px rgba(0,0,0,.2);display:none;outline:none;overflow:hidden;position:absolute;right:8px;top:62px;-webkit-animation:gb__a .2s;animation:gb__a .2s;border-radius:2px;-webkit-user-select:text}.gb_v.gb_Fa .gb_cf,.gb_v.gb_Fa .gb_df,.gb_v.gb_Fa .gb_0,.gb_Fa.gb_0{display:block}.gb_v.gb_Fa.gb_ef .gb_cf,.gb_v.gb_Fa.gb_ef .gb_df{display:none}.gb_Nd{position:absolute;right:8px;top:62px;z-index:-1}.gb_2a .gb_cf,.gb_2a .gb_df,.gb_2a .gb_0{margin-top:-10px}.gb_v:first-child,#gbsfw:first-child+.gb_v{padding-left:4px}.gb_Ka.gb_Od .gb_v:first-child{padding-left:0}.gb_Pd{position:relative}.gb_t.gb_vd.gb_9a.gb_kd{margin:0 12px;padding:0}.gb_t .gb_d{position:relative}.gb_t .gb_v{margin:0 4px;padding:4px}.gb_t .gb_Qd{display:inline-block}.gb_t a.gb_gd{-webkit-box-align:center;-webkit-align-items:center;-webkit-align-items:center;align-items:center;-webkit-border-radius:100px;border-radius:100px;border:0;background:#0b57d0;color:#fff;display:-webkit-inline-box;display:-webkit-inline-flex;display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;font-size:14px;font-weight:500;height:40px;white-space:nowrap;width:auto}.gb_t a.gb_d.gb_gd{margin:0 4px;padding:4px 24px 4px 24px}.gb_t a.gb_gd.gb_Rd{padding:9px 12px 9px 16px}.gb_t a.gb_gd.gb_Sd{background:transparent;border:1px solid #747775;color:#0b57d0;outline:0}.gb_t .gb_s{fill:#0b57d0}.gb_t .gb_Td{fill:#0b57d0;margin-left:8px}.gb_t .gb_Td circle{fill:#fff}.gb_t .gb_gd .gb_Dd{-webkit-box-flex:1;-webkit-flex-grow:1;-webkit-box-flex:1;box-flex:1;-webkit-flex-grow:1;flex-grow:1;text-align:center}.gb_t .gb_gd:hover{background:#3763cd}.gb_t .gb_gd:hover .gb_Td{fill:#3763cd}.gb_t .gb_gd:focus,.gb_t .gb_gd:active,.gb_t .gb_gd:focus:hover,.gb_t .gb_gd[aria-expanded\x3dtrue],.gb_t .gb_gd:hover[aria-expanded\x3dtrue]{background:#416acf}.gb_t .gb_gd:focus .gb_Td,.gb_t .gb_gd:active .gb_Td,.gb_t .gb_gd:focus:hover .gb_Td,.gb_t .gb_gd[aria-expanded\x3dtrue] .gb_Td,.gb_t .gb_gd:hover[aria-expanded\x3dtrue] .gb_Td{fill:#416acf}.gb_t .gb_gd:focus,.gb_t .gb_gd:active,.gb_t .gb_gd[aria-expanded\x3dtrue]{-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_t .gb_gd:focus-visible{outline:1px solid #416acf;outline-offset:2px}.gb_t .gb_Aa:focus-visible{outline:1px solid #416acf}.gb_t .gb_j.gb_gd{background:#a8c7fa;color:#062e6f}.gb_t .gb_j.gb_gd .gb_Td{fill:#a8c7fa}.gb_t .gb_j.gb_gd .gb_Td circle{fill:#062e6f}.gb_t .gb_j.gb_gd:hover{background:#b4cbf6}.gb_t .gb_j.gb_gd:hover .gb_Td{fill:#b4cbf6}.gb_t .gb_j.gb_gd:focus,.gb_t .gb_j.gb_gd:focus:hover,.gb_t .gb_j.gb_gd:active,.gb_t .gb_j.gb_gd[aria-expanded\x3dtrue],.gb_t .gb_j.gb_gd:hover[aria-expanded\x3dtrue]{background:#b8cdf7}.gb_t .gb_j.gb_gd:focus .gb_Td,.gb_t .gb_j.gb_gd:focus:hover .gb_Td,.gb_t .gb_j.gb_gd:active .gb_Td,.gb_t .gb_j.gb_gd[aria-expanded\x3dtrue] .gb_Td,.gb_t .gb_j.gb_gd:hover[aria-expanded\x3dtrue] .gb_Td{fill:#b8cdf7}.gb_t .gb_j.gb_gd:focus-visible{outline-color:#b8cdf7}.gb_t .gb_j.gb_gd:focus,.gb_t .gb_j.gb_gd:active,.gb_t .gb_j.gb_gd[aria-expanded\x3dtrue]{-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_t .gb_gd.gb_Sd:hover,.gb_t .gb_gd.gb_Sd:focus,.gb_t .gb_gd.gb_Sd[aria-expanded\x3dtrue],.gb_t .gb_gd.gb_Sd:hover[aria-expanded\x3dtrue]{background:rgba(11,87,208,.08);-webkit-box-shadow:none;box-shadow:none}.gb_t .gb_gd.gb_Sd:active{background:rgba(11,87,208,.12);-webkit-box-shadow:none;box-shadow:none}.gb_t .gb_gd.gb_Sd:focus-visible{border-color:#0b57d0;outline:0}.gb_t .gb_j.gb_gd.gb_Sd{background:transparent;color:#a8c7fa}.gb_t .gb_j.gb_gd.gb_Sd:hover,.gb_t .gb_j.gb_gd.gb_Sd:focus,.gb_t .gb_j.gb_gd.gb_Sd[aria-expanded\x3dtrue],.gb_t .gb_j.gb_gd.gb_Sd:hover[aria-expanded\x3dtrue]{background:rgba(168,199,250,.08);-webkit-box-shadow:none;box-shadow:none}.gb_t .gb_j.gb_gd.gb_Sd:active{background:rgba(168,199,250,.12);-webkit-box-shadow:none;box-shadow:none}.gb_t .gb_j.gb_gd.gb_Sd:focus-visible{border-color:#a8c7fa;outline:0}.gb_j .gb_t .gb_s{fill:#a8c7fa}.gb_j .gb_t .gb_Aa:focus-visible{outline-color:#a8c7fa}.gb_0c .gb_Pd,.gb_f .gb_Pd{float:right}.gb_d{padding:8px;cursor:pointer}.gb_d:after{content:\x22\x22;position:absolute;top:-4px;bottom:-4px;left:-4px;right:-4px}.gb_Ka .gb_he:not(.gb_sa):focus img{background-color:rgba(0,0,0,.2);outline:none;-webkit-border-radius:50%;border-radius:50%}.gb_Ud button svg,.gb_d{-webkit-border-radius:50%;border-radius:50%}.gb_Ud button:focus:not(:focus-visible) svg,.gb_Ud button:hover svg,.gb_Ud button:active svg,.gb_d:focus:not(:focus-visible),.gb_d:hover,.gb_d:active,.gb_d[aria-expanded\x3dtrue]{outline:none}.gb_Jc .gb_Ud.gb_qe button:focus-visible svg,.gb_Ud button:focus-visible svg,.gb_d:focus-visible{outline:1px solid #202124}.gb_Jc .gb_Ud button:focus-visible svg,.gb_Jc .gb_d:focus-visible{outline:1px solid #f1f3f4}@media (forced-colors:active){.gb_Jc .gb_Ud.gb_qe button:focus-visible svg,.gb_Ud button:focus-visible svg,.gb_Jc .gb_Ud button:focus-visible svg{outline:1px solid currentcolor}}.gb_Jc .gb_Ud.gb_qe button:focus svg,.gb_Jc .gb_Ud.gb_qe button:focus:hover svg,.gb_Ud button:focus svg,.gb_Ud button:focus:hover svg,.gb_d:focus,.gb_d:focus:hover{background-color:rgba(60,64,67,.1)}.gb_Jc .gb_Ud.gb_qe button:active svg,.gb_Ud button:active svg,.gb_d:active{background-color:rgba(60,64,67,.12)}.gb_Jc .gb_Ud.gb_qe button:hover svg,.gb_Ud button:hover svg,.gb_d:hover{background-color:rgba(60,64,67,.08)}.gb_ya .gb_d.gb_Aa:hover{background-color:transparent}.gb_d[aria-expanded\x3dtrue],.gb_d:hover[aria-expanded\x3dtrue]{background-color:rgba(95,99,104,.24)}.gb_d[aria-expanded\x3dtrue] .gb_i{fill:#5f6368;opacity:1}.gb_Jc .gb_Ud button:hover svg,.gb_Jc .gb_d:hover{background-color:rgba(232,234,237,.08)}.gb_Jc .gb_Ud button:focus svg,.gb_Jc .gb_Ud button:focus:hover svg,.gb_Jc .gb_d:focus,.gb_Jc .gb_d:focus:hover{background-color:rgba(232,234,237,.1)}.gb_Jc .gb_Ud button:active svg,.gb_Jc .gb_d:active{background-color:rgba(232,234,237,.12)}.gb_Jc .gb_d[aria-expanded\x3dtrue],.gb_Jc .gb_d:hover[aria-expanded\x3dtrue]{background-color:rgba(255,255,255,.12)}.gb_Jc .gb_d[aria-expanded\x3dtrue] .gb_i{fill:#fff;opacity:1}.gb_v{padding:4px}.gb_Ka.gb_Od .gb_v{padding:4px 2px}.gb_Ka.gb_Od .gb_b.gb_v{padding-left:6px}.gb_0{z-index:991;line-height:normal}.gb_0.gb_Vd{left:0;right:auto}@media (max-width:350px){.gb_0.gb_Vd{left:0}}.gb_Wd .gb_0{top:56px}.gb_l .gb_d,.gb_Z .gb_l .gb_d{background-position:-64px -29px}.gb_E .gb_l .gb_d{background-position:-29px -29px;opacity:1}.gb_l .gb_d,.gb_l .gb_d:hover,.gb_l .gb_d:focus{opacity:1}.gb_ed{display:none}@media screen and (max-width:319px){.gb_ld:not(.gb_qd) .gb_l{display:none;visibility:hidden}}.gb_o{display:none}.gb_8c{font-family:Google Sans,Roboto,Helvetica,Arial,sans-serif;font-size:20px;font-weight:400;letter-spacing:0.25px;line-height:48px;margin-bottom:2px;opacity:1;overflow:hidden;padding-left:16px;position:relative;text-overflow:ellipsis;vertical-align:middle;top:2px;white-space:nowrap;-webkit-flex:1 1 auto;-webkit-box-flex:1;flex:1 1 auto}.gb_8c.gb_9c{color:#3c4043}.gb_Ka.gb_La .gb_8c{margin-bottom:0}.gb_ad.gb_bd .gb_8c{padding-left:4px}.gb_Ka.gb_La .gb_cd{position:relative;top:-2px}.gb_Ka{color:black;min-width:160px;position:relative;-webkit-transition:box-shadow 250ms;transition:box-shadow 250ms}.gb_Ka.gb_Rc{min-width:120px}.gb_Ka.gb_jd .gb_kd{display:none}.gb_Ka.gb_jd .gb_ld{height:56px}header.gb_Ka{display:block}.gb_Ka svg{fill:currentColor}.gb_md{position:fixed;top:0;width:100%}.gb_nd{-webkit-box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2)}.gb_od{height:64px}.gb_ld{-webkit-box-sizing:border-box;box-sizing:border-box;position:relative;width:100%;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-pack:space-between;-webkit-justify-content:space-between;justify-content:space-between;min-width:-webkit-min-content;min-width:min-content}.gb_Ka:not(.gb_La) .gb_ld{padding:8px}.gb_Ka.gb_pd .gb_ld{-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_Ka .gb_ld.gb_qd.gb_rd{min-width:0}.gb_Ka.gb_La .gb_ld{padding:4px;padding-left:8px;min-width:0}.gb_kd{height:48px;vertical-align:middle;white-space:nowrap;-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-user-select:none}.gb_td\x3e.gb_kd{display:table-cell;width:100%}.gb_ad{padding-right:30px;box-sizing:border-box;-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_Ka.gb_La .gb_ad{padding-right:14px}.gb_ud{-webkit-flex:1 1 100%;-webkit-box-flex:1;flex:1 1 100%}.gb_ud\x3e:only-child{display:inline-block}.gb_vd.gb_1c{padding-left:4px}.gb_vd.gb_wd,.gb_Ka.gb_pd .gb_vd,.gb_Ka.gb_La:not(.gb_f) .gb_vd{padding-left:0}.gb_Ka.gb_La .gb_vd.gb_wd{padding-right:0}.gb_Ka.gb_La .gb_vd.gb_wd .gb_ya{margin-left:10px}.gb_1c{display:inline}.gb_Ka.gb_Uc .gb_vd.gb_xd,.gb_Ka.gb_f .gb_vd.gb_xd{padding-left:2px}.gb_8c{display:inline-block}.gb_vd{-webkit-box-sizing:border-box;box-sizing:border-box;height:48px;line-height:normal;padding:0 4px;padding-left:30px;-webkit-flex:0 0 auto;-webkit-box-flex:0;flex:0 0 auto;-webkit-box-pack:flex-end;-webkit-justify-content:flex-end;justify-content:flex-end}.gb_f{height:48px}.gb_Ka.gb_f{min-width:auto}.gb_f .gb_vd{float:right;padding-left:32px}.gb_f .gb_vd.gb_yd{padding-left:0}.gb_zd{font-size:14px;max-width:200px;overflow:hidden;padding:0 12px;text-overflow:ellipsis;white-space:nowrap;-webkit-user-select:text}.gb_fd{-webkit-transition:background-color .4s;-webkit-transition:background-color .4s;transition:background-color .4s}.gb_Fd{color:black}.gb_Jc{color:white}.gb_Ka a,.gb_Oc a{color:inherit}.gb_P{color:rgba(0,0,0,.87)}.gb_Ka svg,.gb_Oc svg,.gb_ad .gb_id,.gb_0c .gb_id{color:#5f6368;opacity:1}.gb_Jc svg,.gb_Oc.gb_Sc svg,.gb_Jc .gb_ad .gb_id,.gb_Jc .gb_ad .gb_Ic,.gb_Jc .gb_ad .gb_cd,.gb_Oc.gb_Sc .gb_id{color:rgba(255,255,255,.87)}.gb_Jc .gb_ad .gb_Hc:not(.gb_Hd){opacity:.87}.gb_9c{color:inherit;opacity:1;text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased}.gb_Jc .gb_9c,.gb_Fd .gb_9c{opacity:1}.gb_Ad{position:relative}.gb_Bd{font-family:arial,sans-serif;line-height:normal;padding-right:15px}a.gb_B,span.gb_B{color:rgba(0,0,0,.87);text-decoration:none}.gb_Jc a.gb_B,.gb_Jc span.gb_B{color:white}a.gb_B:focus{outline-offset:2px}a.gb_B:hover{text-decoration:underline}.gb_C{display:inline-block;padding-left:15px}.gb_C .gb_B{display:inline-block;line-height:24px;vertical-align:middle}.gb_Id{font-family:Google Sans,Roboto,Helvetica,Arial,sans-serif;font-weight:500;font-size:14px;letter-spacing:.25px;line-height:16px;margin-left:10px;margin-right:8px;min-width:96px;padding:9px 23px;text-align:center;vertical-align:middle;border-radius:4px;box-sizing:border-box}.gb_Ka.gb_f .gb_Id{margin-left:8px}#gb a.gb_wa.gb_Id{cursor:pointer}.gb_wa.gb_Id:hover{background:#1b66c9;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_wa.gb_Id:focus,.gb_wa.gb_Id:hover:focus{background:#1c5fba;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_wa.gb_Id:active{background:#1b63c1;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_Id{background:#1a73e8;border:1px solid transparent}.gb_Ka.gb_La .gb_Id{padding:9px 15px;min-width:80px}.gb_Cd{text-align:left}#gb .gb_Jc a.gb_Id:not(.gb_j),#gb.gb_Jc a.gb_Id:not(.gb_Jd){background:#fff;border-color:#dadce0;-webkit-box-shadow:none;box-shadow:none;color:#1a73e8}#gb a.gb_wa.gb_j.gb_Id{background:#8ab4f8;border:1px solid transparent;-webkit-box-shadow:none;box-shadow:none;color:#202124}#gb .gb_Jc a.gb_Id:hover:not(.gb_j),#gb.gb_Jc a.gb_Id:not(.gb_Jd):hover{background:#f8fbff;border-color:#cce0fc}#gb a.gb_wa.gb_j.gb_Id:hover{background:#93baf9;border-color:transparent;-webkit-box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.3);box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.3)}#gb .gb_Jc a.gb_Id:focus:not(.gb_j),#gb .gb_Jc a.gb_Id:focus:hover:not(.gb_j),#gb.gb_Jc a.gb_Id:focus:not(.gb_j),#gb.gb_Jc a.gb_Id:focus:hover:not(.gb_j){background:#f4f8ff;outline:1px solid #c9ddfc}#gb a.gb_wa.gb_j.gb_Id:focus,#gb a.gb_wa.gb_j.gb_Id:focus:hover{background:#a6c6fa;border-color:transparent;-webkit-box-shadow:none;box-shadow:none}#gb .gb_Jc a.gb_Id:active:not(.gb_j),#gb.gb_Jc a.gb_Id:not(.gb_Jd):active{background:#ecf3fe}#gb a.gb_wa.gb_j.gb_Id:active{background:#a1c3f9;-webkit-box-shadow:0 1px 2px rgba(60,64,67,.3),0 2px 6px 2px rgba(60,64,67,.15);box-shadow:0 1px 2px rgba(60,64,67,.3),0 2px 6px 2px rgba(60,64,67,.15)}.gb_Kd{display:none}@media screen and (max-width:319px){.gb_ld:not(.gb_qd) .gb_l{display:none;visibility:hidden}}.gb_ya{background-color:rgba(255,255,255,.88);border:1px solid #dadce0;-webkit-box-sizing:border-box;box-sizing:border-box;cursor:pointer;display:inline-block;max-height:48px;overflow:hidden;outline:none;padding:0;vertical-align:middle;width:134px;-webkit-border-radius:8px;border-radius:8px}.gb_ya.gb_j{background-color:transparent;border:1px solid #5f6368}.gb_Ea{display:inherit}.gb_ya.gb_j .gb_Ea{background:#fff;-webkit-border-radius:4px;border-radius:4px;display:inline-block;left:8px;margin-right:5px;position:relative;padding:3px;top:-1px}.gb_ya:hover{border:1px solid #d2e3fc;background-color:rgba(248,250,255,.88)}.gb_ya.gb_j:hover{background-color:rgba(241,243,244,.04);border:1px solid #5f6368}.gb_ya:focus-visible,.gb_ya:focus{background-color:#fff;outline:1px solid #202124;-webkit-box-shadow:0 1px 2px 0 rgba(60,64,67,.3),0 1px 3px 1px rgba(60,64,67,.15);box-shadow:0 1px 2px 0 rgba(60,64,67,.3),0 1px 3px 1px rgba(60,64,67,.15)}.gb_ya.gb_j:focus-visible,.gb_ya.gb_j:focus{background-color:rgba(241,243,244,.12);outline:1px solid #f1f3f4;-webkit-box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px 0 rgba(0,0,0,.3);box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px 0 rgba(0,0,0,.3)}.gb_ya.gb_j:active,.gb_ya.gb_Fa.gb_j:focus{background-color:rgba(241,243,244,.1);border:1px solid #5f6368}.gb_Ha{display:inline-block;padding-bottom:2px;padding-left:7px;padding-top:2px;text-align:center;vertical-align:middle;line-height:32px;width:78px}.gb_ya.gb_j .gb_Ha{line-height:26px;margin-left:0;padding-bottom:0;padding-left:0;padding-top:0;width:72px}.gb_Ha.gb_Ia{background-color:#f1f3f4;-webkit-border-radius:4px;border-radius:4px;margin-left:8px;padding-left:0;line-height:30px}.gb_Ha.gb_Ia .gb_Ja{vertical-align:middle}.gb_Ka:not(.gb_La) .gb_ya{margin-left:10px;margin-right:4px}.gb_Ma{max-height:32px;width:78px}.gb_ya.gb_j .gb_Ma{max-height:26px;width:72px}.gb_n{-webkit-background-size:32px 32px;background-size:32px 32px;border:0;-webkit-border-radius:50%;border-radius:50%;display:block;margin:0px;position:relative;height:32px;width:32px;z-index:0}.gb_Wa{background-color:#e8f0fe;border:1px solid rgba(32,33,36,.08);position:relative}.gb_Wa.gb_n{height:30px;width:30px}.gb_Wa.gb_n:hover,.gb_Wa.gb_n:active{-webkit-box-shadow:none;box-shadow:none}.gb_Xa{background:#fff;border:none;-webkit-border-radius:50%;border-radius:50%;bottom:2px;-webkit-box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);height:14px;margin:2px;position:absolute;right:0;width:14px}.gb_Za{color:#1f71e7;font:400 22px/32px Google Sans,Roboto,Helvetica,Arial,sans-serif;text-align:center;text-transform:uppercase}@media (-webkit-min-device-pixel-ratio:1.25),(min-resolution:1.25dppx),(min-device-pixel-ratio:1.25){.gb_n::before,.gb_0a::before{display:inline-block;-webkit-transform:scale(0.5);-webkit-transform:scale(0.5);transform:scale(0.5);-webkit-transform-origin:left 0;-webkit-transform-origin:left 0;transform-origin:left 0}.gb_H .gb_0a::before{-webkit-transform:scale(scale(0.416666667));-webkit-transform:scale(scale(0.416666667));transform:scale(scale(0.416666667))}}.gb_n:hover,.gb_n:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15);box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_n:active{-webkit-box-shadow:inset 0 2px 0 rgba(0,0,0,.15);box-shadow:inset 0 2px 0 rgba(0,0,0,.15)}.gb_n:active::after{background:rgba(0,0,0,.1);-webkit-border-radius:50%;border-radius:50%;content:\x22\x22;display:block;height:100%}.gb_1a{cursor:pointer;line-height:40px;min-width:30px;opacity:.75;overflow:hidden;vertical-align:middle;text-overflow:ellipsis}.gb_d.gb_1a{width:auto}.gb_1a:hover,.gb_1a:focus{opacity:.85}.gb_2a .gb_1a,.gb_2a .gb_3a{line-height:26px}#gb#gb.gb_2a a.gb_1a,.gb_2a .gb_3a{font-size:11px;height:auto}.gb_4a{border-top:4px solid #000;border-left:4px dashed transparent;border-right:4px dashed transparent;display:inline-block;margin-left:6px;opacity:.75;vertical-align:middle}.gb_Aa:hover .gb_4a{opacity:.85}.gb_ya\x3e.gb_b{padding:3px 3px 3px 4px}.gb_5a.gb_Va{color:#fff}.gb_E .gb_1a,.gb_E .gb_4a{opacity:1}#gb#gb.gb_E.gb_E a.gb_1a,#gb#gb .gb_E.gb_E a.gb_1a{color:#fff}.gb_E.gb_E .gb_4a{border-top-color:#fff;opacity:1}.gb_Z .gb_n:hover,.gb_E .gb_n:hover,.gb_Z .gb_n:focus,.gb_E .gb_n:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2);box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2)}.gb_6a .gb_b,.gb_7a .gb_b{position:absolute;right:1px}.gb_b.gb_D,.gb_8a.gb_D,.gb_Aa.gb_D{-webkit-flex:0 1 auto;-webkit-box-flex:0;flex:0 1 auto}.gb_9a.gb_ab .gb_1a{width:30px!important}.gb_m{height:40px;position:absolute;right:-5px;top:-5px;width:40px}.gb_bb .gb_m,.gb_cb .gb_m{right:0;top:0}.gb_b .gb_d{padding:4px}.gb_q{display:none}sentinel{}\x3c/style\x3e', function() {
                        ;this.gbar_ = {
                            CONFIG: [[[0, "www.gstatic.com", "og.qtm.en_US.-KwF7ICUAF4.2019.O", "com.vn", "vi", "1", 1, [4, 2, "", "", "", "594992896", "0"], null, "WrGXZYrVGtK50-kP9aa-qAM", null, 0, "og.qtm.c3t_I6Mp0HE.L.W.O", "AA2YrTsm9bnnNsIEwTZ8BulPkzYk6RT7Dg", "AA2YrTvznsPFDYlyVbrtMHXhEFPaBzzz_g", "", 2, 1, 200, "VNM", null, null, "1", "1", 1, null, null, 89978449], null, [1, 0.1000000014901161, 2, 1], null, [1, 0, 0, null, "0", "ngockhoannk@gmail.com", "", "AIA20m7VGh6VEBloCUEC3n-PhT99zDEy3Cw8dq_eELy-Zf__Q2pU9nwng1-zhDPqlpHeeaODCUDGeuyH5C9ZiVtgJyoX5a9rFA", 0, 0, 0], [0, 0, "", 1, 0, 0, 0, 0, 0, 0, null, 0, 0, null, 0, 0, null, null, 0, 0, 0, "", "", "", "", "", "", null, 0, 0, 0, 0, 0, null, null, null, "rgba(32,33,36,1)", "rgba(255,255,255,1)", 0, 0, 1, null, null, 1, 0, 0], ["%1$s (mặc định)", "Tài khoản thương hiệu", 0, "%1$s (uỷ nhiệm)", 1, null, 83, "https://www.google.com/webhp?authuser=$authuser", null, null, null, 1, "https://accounts.google.com/ListAccounts?listPages=0\u0026authuser=0\u0026pid=1\u0026gpsia=1\u0026source=ogb\u0026atic=1\u0026mo=1\u0026mn=1\u0026hl=vi\u0026ts=157", 0, "dashboard", null, null, null, null, "Hồ sơ", "", 0, null, "Đã đăng xuất", "https://accounts.google.com/AccountChooser?source=ogb\u0026continue=$continue\u0026Email=$email\u0026ec=GAhAAQ", "https://accounts.google.com/RemoveLocalAccount?source=ogb", "Xóa", "Đăng nhập", 0, 1, 1, 0, 1, 1, 0, null, null, null, "Phiên đăng nhập đã hết hạn", null, null, null, "Khách vãng lai", null, "Mặc định", "Được ủy quyền", "Đăng xuất khỏi tất cả tài khoản", 1, null, null, 0, null, null, "myaccount.google.com", "https", 0, 1, 0], null, ["1", "gci_91f30755d6a6b787dcc2a4062e6e9824.js", "googleapis.client:gapi.iframes", "0", "vi"], null, null, null, null, ["m;/_/scs/abc-static/_/js/k=gapi.gapi.en.GsbA68hXs80.O/d=1/rs=AHpOoo899t-H8Lxb3OqzMDuPn6TV_i36ag/m=__features__", "https://apis.google.com", "", "", "1", "", null, 1, "es_plusone_gc_20231128.0_p1", "vi", null, 0], [0.009999999776482582, "com.vn", "1", [null, "", "0", null, 1, 5184000, null, null, "", null, null, null, null, null, 0, null, 0, null, 1, 0, 0, 0, null, null, 0, 0, null, 0, 0, 0, 0, 0], null, null, null, 0, null, null, ["5061451", "google\\.(com|ru|ca|by|kz|com\\.mx|com\\.tr)$", 1]], [1, 1, null, 40400, 1, "VNM", "vi", "594992896.0", 8, 0.009999999776482582, 1, 0, null, null, null, null, "3700949,3701183,3701185", null, null, null, "WrGXZYrVGtK50-kP9aa-qAM", 0, 1, 0, null, 2, 5, "ta", 96, 0, 0, 1, 1, 1, 89978449], [[null, null, null, "https://www.gstatic.com/og/_/js/k=og.qtm.en_US.-KwF7ICUAF4.2019.O/rt=j/m=qabr,qgl,q_dnp,qcwid,qapid,qrcd,q_dg/exm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/rs=AA2YrTsm9bnnNsIEwTZ8BulPkzYk6RT7Dg"], [null, null, null, "https://www.gstatic.com/og/_/ss/k=og.qtm.c3t_I6Mp0HE.L.W.O/m=qcwid/excm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/ct=zgms/rs=AA2YrTvznsPFDYlyVbrtMHXhEFPaBzzz_g"]], null, null, null, [[[null, null, [null, null, null, "https://ogs.google.com/u/0/widget/app?awwd=1\u0026gm3=1"], 0, 470, 370, 50, 4, 1, 0, 0, 63, 64, 8000, "https://www.google.com.vn/intl/vi/about/products?tab=wh", 67, 1, 69, null, 1, 70, "Đã xảy ra lỗi khi đang tải bộ ứng dụng. Vui lòng thử lại sau vài phút hoặc chuyển đến trang %1$sCác sản phẩm của Google%2$s.", 3, 0, 0, 74, 4000, null, null, null, null, null, null, null, "/widget/app", null, null, null, null, null, null, null, 0], [null, null, [null, null, null, "https://ogs.google.com/u/0/widget/account?amf=1\u0026amb=1\u0026sea=1"], 0, 414, 436, 50, 4, 1, 0, 0, 65, 66, 8000, "https://accounts.google.com/SignOutOptions?hl=vi\u0026continue=https://www.google.com/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw%253A1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26udm%3D%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\u0026ec=GBRAAQ", 68, 2, null, null, 1, 113, "Đã xảy ra lỗi.%1$s Hãy làm mới để thử lại hoặc %2$schọn một tài khoản khác%3$s.", 3, null, null, 75, 0, null, null, null, null, null, null, null, "/widget/account", ["https", "myaccount.google.com", 0, 32, 83, 0], 0, 0, 1, ["Cảnh báo bảo mật quan trọng", "Cảnh báo quan trọng về tài khoản"], 0, 1, null, 1, 1, 0, 0]], null, null, "1", "1", 1, 0, null, "vi", 1, ["https://www.google.com/webhp?authuser=$authuser", "https://accounts.google.com/AddSession?hl=vi\u0026continue=https://www.google.com/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw%253A1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26udm%3D%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\u0026ec=GAlAAQ", "https://accounts.google.com/Logout?hl=vi\u0026continue=https://www.google.com/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw%253A1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26udm%3D%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\u0026timeStmp=1704440154\u0026secTok=.AG5fkS_-LvlIwLfNF6oKSYLauUum_t8_wQ\u0026ec=GAdAAQ", "https://accounts.google.com/ListAccounts?listPages=0\u0026authuser=0\u0026pid=1\u0026gpsia=1\u0026source=ogb\u0026atic=1\u0026mo=1\u0026mn=1\u0026hl=vi\u0026ts=157", 0, 0, "", 0, 0, null, 0, 0, "https://accounts.google.com/ServiceLogin?hl=vi\u0026passive=true\u0026continue=https://www.google.com/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw%253A1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26udm%3D%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\u0026ec=GAZAAQ", 0, 0], 0, 0, 0, null, 0], null, null, [[null, null, null, "https://accounts.google.com/RotateCookiesPage"], 3, 4000, 1, 0, 3701183, 0]]],
                        };
                        this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                _._F_toggles_initialize = function(a) {
                                    ("undefined" !== typeof globalThis ? globalThis : "undefined" !== typeof self ? self : this)._F_toggles = a || []
                                }
                                ;
                                (0,
                                _._F_toggles_initialize)([]);
                                /*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
                                var ea, ka, na, oa, wa, xa, ya, za, Aa, Da, Ea, Fa, Ia, Va, Ua, Ya, $a, Za, ab, bb, lb;
                                _.aa = function(a, b) {
                                    if (Error.captureStackTrace)
                                        Error.captureStackTrace(this, _.aa);
                                    else {
                                        const c = Error().stack;
                                        c && (this.stack = c)
                                    }
                                    a && (this.message = String(a));
                                    void 0 !== b && (this.cause = b)
                                }
                                ;
                                _.ba = function() {
                                    var a = _.q.navigator;
                                    return a && (a = a.userAgent) ? a : ""
                                }
                                ;
                                ea = function(a) {
                                    return ca ? da ? da.brands.some(({brand: b})=>b && -1 != b.indexOf(a)) : !1 : !1
                                }
                                ;
                                _.t = function(a) {
                                    return -1 != _.ba().indexOf(a)
                                }
                                ;
                                _.fa = function() {
                                    return ca ? !!da && 0 < da.brands.length : !1
                                }
                                ;
                                _.ha = function() {
                                    return _.fa() ? !1 : _.t("Opera")
                                }
                                ;
                                _.ia = function() {
                                    return _.fa() ? !1 : _.t("Trident") || _.t("MSIE")
                                }
                                ;
                                _.ja = function() {
                                    return _.t("Firefox") || _.t("FxiOS")
                                }
                                ;
                                _.la = function() {
                                    return _.t("Safari") && !(ka() || (_.fa() ? 0 : _.t("Coast")) || _.ha() || (_.fa() ? 0 : _.t("Edge")) || (_.fa() ? ea("Microsoft Edge") : _.t("Edg/")) || (_.fa() ? ea("Opera") : _.t("OPR")) || _.ja() || _.t("Silk") || _.t("Android"))
                                }
                                ;
                                ka = function() {
                                    return _.fa() ? ea("Chromium") : (_.t("Chrome") || _.t("CriOS")) && !(_.fa() ? 0 : _.t("Edge")) || _.t("Silk")
                                }
                                ;
                                _.ma = function() {
                                    return _.t("Android") && !(ka() || _.ja() || _.ha() || _.t("Silk"))
                                }
                                ;
                                na = function() {
                                    return ca ? !!da && !!da.platform : !1
                                }
                                ;
                                oa = function() {
                                    return _.t("iPhone") && !_.t("iPod") && !_.t("iPad")
                                }
                                ;
                                _.pa = function() {
                                    return oa() || _.t("iPad") || _.t("iPod")
                                }
                                ;
                                _.qa = function() {
                                    return na() ? "macOS" === da.platform : _.t("Macintosh")
                                }
                                ;
                                _.sa = function(a, b) {
                                    return 0 <= _.ra(a, b)
                                }
                                ;
                                _.ta = function(a) {
                                    let b = ""
                                      , c = 0;
                                    const d = a.length - 10240;
                                    for (; c < d; )
                                        b += String.fromCharCode.apply(null, a.subarray(c, c += 10240));
                                    b += String.fromCharCode.apply(null, c ? a.subarray(c) : a);
                                    return btoa(b)
                                }
                                ;
                                _.ua = function(a) {
                                    return null != a && a instanceof Uint8Array
                                }
                                ;
                                _.va = function(a) {
                                    return Array.prototype.slice.call(a)
                                }
                                ;
                                wa = function(a) {
                                    const b = a[_.v] | 0;
                                    1 !== (b & 1) && (Object.isFrozen(a) && (a = _.va(a)),
                                    a[_.v] = b | 1)
                                }
                                ;
                                xa = function() {
                                    var a = [];
                                    a[_.v] |= 1;
                                    return a
                                }
                                ;
                                ya = function(a, b) {
                                    b[_.v] = (a | 0) & -14591
                                }
                                ;
                                za = function(a, b) {
                                    b[_.v] = (a | 34) & -14557
                                }
                                ;
                                Aa = function(a) {
                                    a = a >> 14 & 1023;
                                    return 0 === a ? 536870912 : a
                                }
                                ;
                                _.Ba = function(a) {
                                    return +!!(a & 512) - 1
                                }
                                ;
                                Da = function(a) {
                                    return !(!a || "object" !== typeof a || a.Ti !== Ca)
                                }
                                ;
                                Ea = function(a) {
                                    return null !== a && "object" === typeof a && !Array.isArray(a) && a.constructor === Object
                                }
                                ;
                                Fa = function(a, b, c) {
                                    if (!Array.isArray(a) || a.length)
                                        return !1;
                                    const d = a[_.v] | 0;
                                    if (d & 1)
                                        return !0;
                                    if (!(b && (Array.isArray(b) ? b.includes(c) : b.has(c))))
                                        return !1;
                                    a[_.v] = d | 1;
                                    return !0
                                }
                                ;
                                _.Ga = function(a) {
                                    if (a & 2)
                                        throw Error();
                                }
                                ;
                                Ia = function(a, b) {
                                    (b = _.Ha ? b[_.Ha] : void 0) && (a[_.Ha] = _.va(b))
                                }
                                ;
                                _.Ja = function(a) {
                                    a = Error(a);
                                    a.__closure__error__context__984382 || (a.__closure__error__context__984382 = {});
                                    a.__closure__error__context__984382.severity = "warning";
                                    return a
                                }
                                ;
                                _.Ka = function(a) {
                                    if (!Number.isFinite(a))
                                        throw _.Ja("enum");
                                    return a | 0
                                }
                                ;
                                _.La = function(a) {
                                    if ("number" !== typeof a)
                                        throw _.Ja("int32");
                                    if (!Number.isFinite(a))
                                        throw _.Ja("int32");
                                    return a | 0
                                }
                                ;
                                _.Ma = function(a) {
                                    if (null != a && "string" !== typeof a)
                                        throw Error();
                                    return a
                                }
                                ;
                                _.Na = function(a) {
                                    return null == a || "string" === typeof a ? a : void 0
                                }
                                ;
                                _.Pa = function(a, b, c) {
                                    if (null != a && "object" === typeof a && a.Sd === _.Oa)
                                        return a;
                                    if (Array.isArray(a)) {
                                        var d = a[_.v] | 0
                                          , e = d;
                                        0 === e && (e |= c & 32);
                                        e |= c & 2;
                                        e !== d && (a[_.v] = e);
                                        return new b(a)
                                    }
                                }
                                ;
                                _.Ra = function(a, b) {
                                    Qa = b;
                                    a = new a(b);
                                    Qa = void 0;
                                    return a
                                }
                                ;
                                _.Ta = function(a, b, c) {
                                    null == a && (a = Qa);
                                    Qa = void 0;
                                    if (null == a) {
                                        var d = 96;
                                        c ? (a = [c],
                                        d |= 512) : a = [];
                                        b && (d = d & -16760833 | (b & 1023) << 14)
                                    } else {
                                        if (!Array.isArray(a))
                                            throw Error();
                                        d = a[_.v] | 0;
                                        if (d & 64)
                                            return _.Sa && delete a[_.Sa],
                                            a;
                                        d |= 64;
                                        if (c && (d |= 512,
                                        c !== a[0]))
                                            throw Error();
                                        a: {
                                            c = a;
                                            const e = c.length;
                                            if (e) {
                                                const f = e - 1;
                                                if (Ea(c[f])) {
                                                    d |= 256;
                                                    b = f - _.Ba(d);
                                                    if (1024 <= b)
                                                        throw Error();
                                                    d = d & -16760833 | (b & 1023) << 14;
                                                    break a
                                                }
                                            }
                                            if (b) {
                                                b = Math.max(b, e - _.Ba(d));
                                                if (1024 < b)
                                                    throw Error();
                                                d = d & -16760833 | (b & 1023) << 14
                                            }
                                        }
                                    }
                                    a[_.v] = d;
                                    return a
                                }
                                ;
                                Va = function(a, b) {
                                    return Ua(b)
                                }
                                ;
                                Ua = function(a) {
                                    switch (typeof a) {
                                    case "number":
                                        return isFinite(a) ? a : String(a);
                                    case "boolean":
                                        return a ? 1 : 0;
                                    case "object":
                                        if (a) {
                                            if (Array.isArray(a))
                                                return Wa || !Fa(a, void 0, 9999) ? a : void 0;
                                            if (_.ua(a))
                                                return _.ta(a);
                                            if ("function" == typeof _.Xa && a instanceof _.Xa)
                                                return a.wg()
                                        }
                                    }
                                    return a
                                }
                                ;
                                Ya = function(a, b, c) {
                                    const d = _.va(a);
                                    var e = d.length;
                                    const f = b & 256 ? d[e - 1] : void 0;
                                    e += f ? -1 : 0;
                                    for (b = b & 512 ? 1 : 0; b < e; b++)
                                        d[b] = c(d[b]);
                                    if (f) {
                                        b = d[b] = {};
                                        for (const g in f)
                                            b[g] = c(f[g])
                                    }
                                    Ia(d, a);
                                    return d
                                }
                                ;
                                $a = function(a, b, c, d, e, f) {
                                    if (null != a) {
                                        if (Array.isArray(a))
                                            a = e && 0 == a.length && (a[_.v] | 0) & 1 ? void 0 : f && (a[_.v] | 0) & 2 ? a : Za(a, b, c, void 0 !== d, e, f);
                                        else if (Ea(a)) {
                                            const g = {};
                                            for (let h in a)
                                                g[h] = $a(a[h], b, c, d, e, f);
                                            a = g
                                        } else
                                            a = b(a, d);
                                        return a
                                    }
                                }
                                ;
                                Za = function(a, b, c, d, e, f) {
                                    const g = d || c ? a[_.v] | 0 : 0;
                                    d = d ? !!(g & 32) : void 0;
                                    const h = _.va(a);
                                    for (let k = 0; k < h.length; k++)
                                        h[k] = $a(h[k], b, c, d, e, f);
                                    c && (Ia(h, a),
                                    c(g, h));
                                    return h
                                }
                                ;
                                ab = function(a) {
                                    return a.Sd === _.Oa ? a.toJSON() : Ua(a)
                                }
                                ;
                                bb = function(a, b, c=za) {
                                    if (null != a) {
                                        if (a instanceof Uint8Array)
                                            return b ? a : new Uint8Array(a);
                                        if (Array.isArray(a)) {
                                            var d = a[_.v] | 0;
                                            if (d & 2)
                                                return a;
                                            b && (b = 0 === d || !!(d & 32) && !(d & 64 || !(d & 16)));
                                            return b ? (a[_.v] = (d | 34) & -12293,
                                            a) : Za(a, bb, d & 4 ? za : c, !0, !1, !0)
                                        }
                                        a.Sd === _.Oa && (c = a.ma,
                                        d = c[_.v],
                                        a = d & 2 ? a : _.Ra(a.constructor, _.cb(c, d, !0)));
                                        return a
                                    }
                                }
                                ;
                                _.cb = function(a, b, c) {
                                    const d = c || b & 2 ? za : ya
                                      , e = !!(b & 32);
                                    a = Ya(a, b, f=>bb(f, e, d));
                                    a[_.v] = a[_.v] | 32 | (c ? 2 : 0);
                                    return a
                                }
                                ;
                                _.db = function(a) {
                                    const b = a.ma
                                      , c = b[_.v];
                                    return c & 2 ? _.Ra(a.constructor, _.cb(b, c, !1)) : a
                                }
                                ;
                                _.eb = function(a, b, c, d, e) {
                                    const f = Aa(b);
                                    if (c >= f || e) {
                                        let g = b;
                                        if (b & 256)
                                            e = a[a.length - 1];
                                        else {
                                            if (null == d)
                                                return g;
                                            e = a[f + _.Ba(b)] = {};
                                            g |= 256
                                        }
                                        e[c] = d;
                                        c < f && (a[c + _.Ba(b)] = void 0);
                                        g !== b && (a[_.v] = g);
                                        return g
                                    }
                                    a[c + _.Ba(b)] = d;
                                    b & 256 && (a = a[a.length - 1],
                                    c in a && delete a[c]);
                                    return b
                                }
                                ;
                                _.gb = function(a, b, c, d) {
                                    a = a.ma;
                                    let e = a[_.v];
                                    const f = _.fb(a, e, c, d);
                                    b = _.Pa(f, b, e);
                                    b !== f && null != b && _.eb(a, e, c, b, d);
                                    return b
                                }
                                ;
                                _.hb = function(a, b) {
                                    return null != a ? a : b
                                }
                                ;
                                lb = function(a, b, c) {
                                    const d = a.constructor.Aa;
                                    var e = (c ? a.ma : b)[_.v]
                                      , f = Aa(e)
                                      , g = !1;
                                    if (d && Wa) {
                                        if (!c) {
                                            b = _.va(b);
                                            var h;
                                            if (b.length && Ea(h = b[b.length - 1]))
                                                for (g = 0; g < d.length; g++)
                                                    if (d[g] >= f) {
                                                        Object.assign(b[b.length - 1] = {}, h);
                                                        break
                                                    }
                                            g = !0
                                        }
                                        f = b;
                                        c = !c;
                                        h = a.ma[_.v];
                                        a = Aa(h);
                                        h = _.Ba(h);
                                        var k;
                                        for (let M = 0; M < d.length; M++) {
                                            var l = d[M];
                                            if (l < a) {
                                                l += h;
                                                var p = f[l];
                                                null == p ? f[l] = c ? _.ib : xa() : c && p !== _.ib && wa(p)
                                            } else {
                                                if (!k) {
                                                    var n = void 0;
                                                    f.length && Ea(n = f[f.length - 1]) ? k = n : f.push(k = {})
                                                }
                                                p = k[l];
                                                null == k[l] ? k[l] = c ? _.ib : xa() : c && p !== _.ib && wa(p)
                                            }
                                        }
                                    }
                                    k = b.length;
                                    if (!k)
                                        return b;
                                    let u, r;
                                    if (Ea(n = b[k - 1])) {
                                        a: {
                                            var z = n;
                                            f = {};
                                            c = !1;
                                            for (var E in z) {
                                                a = z[E];
                                                if (Array.isArray(a)) {
                                                    h = a;
                                                    if (!jb && Fa(a, d, +E) || !kb && Da(a) && 0 === a.size)
                                                        a = null;
                                                    a != h && (c = !0)
                                                }
                                                null != a ? f[E] = a : c = !0
                                            }
                                            if (c) {
                                                for (let M in f) {
                                                    z = f;
                                                    break a
                                                }
                                                z = null
                                            }
                                        }
                                        z != n && (u = !0);
                                        k--
                                    }
                                    for (e = _.Ba(e); 0 < k; k--) {
                                        E = k - 1;
                                        n = b[E];
                                        if (!(null == n || !jb && Fa(n, d, E - e) || !kb && Da(n) && 0 === n.size))
                                            break;
                                        r = !0
                                    }
                                    if (!u && !r)
                                        return b;
                                    var J;
                                    g ? J = b : J = Array.prototype.slice.call(b, 0, k);
                                    b = J;
                                    g && (b.length = k);
                                    z && b.push(z);
                                    return b
                                }
                                ;
                                _.w = function(a, b) {
                                    return null != a ? !!a : !!b
                                }
                                ;
                                _.x = function(a, b) {
                                    void 0 == b && (b = "");
                                    return null != a ? a : b
                                }
                                ;
                                _.mb = function(a, b) {
                                    void 0 == b && (b = 0);
                                    return null != a ? a : b
                                }
                                ;
                                _.ob = function(a, b) {
                                    let c, d;
                                    for (let e = 1; e < arguments.length; e++) {
                                        d = arguments[e];
                                        for (c in d)
                                            a[c] = d[c];
                                        for (let f = 0; f < nb.length; f++)
                                            c = nb[f],
                                            Object.prototype.hasOwnProperty.call(d, c) && (a[c] = d[c])
                                    }
                                }
                                ;
                                var rb, sb, wb, xb;
                                _.pb = _.pb || {};
                                _.q = this || self;
                                rb = function(a, b) {
                                    var c = _.qb("WIZ_global_data.oxN3nb");
                                    a = c && c[a];
                                    return null != a ? a : b
                                }
                                ;
                                sb = _.q._F_toggles || [];
                                _.qb = function(a, b) {
                                    a = a.split(".");
                                    b = b || _.q;
                                    for (var c = 0; c < a.length; c++)
                                        if (b = b[a[c]],
                                        null == b)
                                            return null;
                                    return b
                                }
                                ;
                                _.tb = function(a) {
                                    var b = typeof a;
                                    return "object" != b ? b : a ? Array.isArray(a) ? "array" : b : "null"
                                }
                                ;
                                _.ub = function(a) {
                                    var b = typeof a;
                                    return "object" == b && null != a || "function" == b
                                }
                                ;
                                _.vb = "closure_uid_" + (1E9 * Math.random() >>> 0);
                                wb = function(a, b, c) {
                                    return a.call.apply(a.bind, arguments)
                                }
                                ;
                                xb = function(a, b, c) {
                                    if (!a)
                                        throw Error();
                                    if (2 < arguments.length) {
                                        var d = Array.prototype.slice.call(arguments, 2);
                                        return function() {
                                            var e = Array.prototype.slice.call(arguments);
                                            Array.prototype.unshift.apply(e, d);
                                            return a.apply(b, e)
                                        }
                                    }
                                    return function() {
                                        return a.apply(b, arguments)
                                    }
                                }
                                ;
                                _.y = function(a, b, c) {
                                    _.y = Function.prototype.bind && -1 != Function.prototype.bind.toString().indexOf("native code") ? wb : xb;
                                    return _.y.apply(null, arguments)
                                }
                                ;
                                _.A = function(a, b) {
                                    a = a.split(".");
                                    var c = _.q;
                                    a[0]in c || "undefined" == typeof c.execScript || c.execScript("var " + a[0]);
                                    for (var d; a.length && (d = a.shift()); )
                                        a.length || void 0 === b ? c[d] && c[d] !== Object.prototype[d] ? c = c[d] : c = c[d] = {} : c[d] = b
                                }
                                ;
                                _.B = function(a, b) {
                                    function c() {}
                                    c.prototype = b.prototype;
                                    a.W = b.prototype;
                                    a.prototype = new c;
                                    a.prototype.constructor = a;
                                    a.Mi = function(d, e, f) {
                                        for (var g = Array(arguments.length - 2), h = 2; h < arguments.length; h++)
                                            g[h - 2] = arguments[h];
                                        return b.prototype[e].apply(d, g)
                                    }
                                }
                                ;
                                _.B(_.aa, Error);
                                _.aa.prototype.name = "CustomError";
                                _.yb = String.prototype.trim ? function(a) {
                                    return a.trim()
                                }
                                : function(a) {
                                    return /^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]
                                }
                                ;
                                var zb = !!(sb[0] & 128)
                                  , Ab = !!(sb[0] & 4)
                                  , Bb = !!(sb[0] & 256)
                                  , Cb = !!(sb[0] & 2);
                                var ca = zb ? Bb : rb(610401301, !1)
                                  , Db = zb ? Ab || !Cb : rb(572417392, !0);
                                var da, Eb = _.q.navigator;
                                da = Eb ? Eb.userAgentData || null : null;
                                _.ra = function(a, b) {
                                    return Array.prototype.indexOf.call(a, b, void 0)
                                }
                                ;
                                _.Fb = function(a, b, c) {
                                    Array.prototype.forEach.call(a, b, c)
                                }
                                ;
                                _.Gb = function(a) {
                                    _.Gb[" "](a);
                                    return a
                                }
                                ;
                                _.Gb[" "] = function() {}
                                ;
                                var Ub, Vb, $b;
                                _.Hb = _.ha();
                                _.C = _.ia();
                                _.Ib = _.t("Edge");
                                _.Jb = _.Ib || _.C;
                                _.Kb = _.t("Gecko") && !(-1 != _.ba().toLowerCase().indexOf("webkit") && !_.t("Edge")) && !(_.t("Trident") || _.t("MSIE")) && !_.t("Edge");
                                _.Mb = -1 != _.ba().toLowerCase().indexOf("webkit") && !_.t("Edge");
                                _.Nb = _.qa();
                                _.Ob = na() ? "Windows" === da.platform : _.t("Windows");
                                _.Pb = na() ? "Android" === da.platform : _.t("Android");
                                _.Qb = oa();
                                _.Rb = _.t("iPad");
                                _.Sb = _.t("iPod");
                                _.Tb = _.pa();
                                Ub = function() {
                                    var a = _.q.document;
                                    return a ? a.documentMode : void 0
                                }
                                ;
                                a: {
                                    var Wb = ""
                                      , Xb = function() {
                                        var a = _.ba();
                                        if (_.Kb)
                                            return /rv:([^\);]+)(\)|;)/.exec(a);
                                        if (_.Ib)
                                            return /Edge\/([\d\.]+)/.exec(a);
                                        if (_.C)
                                            return /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);
                                        if (_.Mb)
                                            return /WebKit\/(\S+)/.exec(a);
                                        if (_.Hb)
                                            return /(?:Version)[ \/]?(\S+)/.exec(a)
                                    }();
                                    Xb && (Wb = Xb ? Xb[1] : "");
                                    if (_.C) {
                                        var Yb = Ub();
                                        if (null != Yb && Yb > parseFloat(Wb)) {
                                            Vb = String(Yb);
                                            break a
                                        }
                                    }
                                    Vb = Wb
                                }
                                _.Zb = Vb;
                                if (_.q.document && _.C) {
                                    var ac = Ub();
                                    $b = ac ? ac : parseInt(_.Zb, 10) || void 0
                                } else
                                    $b = void 0;
                                _.bc = $b;
                                _.cc = _.ja();
                                _.dc = oa() || _.t("iPod");
                                _.ec = _.t("iPad");
                                _.fc = _.ma();
                                _.gc = ka();
                                _.hc = _.la() && !_.pa();
                                var kb = !Db
                                  , jb = !Db;
                                _.ic = "undefined" !== typeof TextDecoder;
                                _.jc = "undefined" !== typeof TextEncoder;
                                _.v = Symbol();
                                var Ca, kc, Wa, lc, mc, nc;
                                _.Oa = {};
                                Ca = {};
                                Wa = !Db;
                                lc = [];
                                lc[_.v] = 55;
                                _.ib = Object.freeze(lc);
                                mc = class {
                                }
                                ;
                                nc = class {
                                }
                                ;
                                Object.freeze(new mc);
                                Object.freeze(new nc);
                                var Qa;
                                _.oc = function(a, b) {
                                    a = a.ma;
                                    return _.fb(a, a[_.v], b)
                                }
                                ;
                                _.fb = function(a, b, c, d) {
                                    if (-1 === c)
                                        return null;
                                    if (c >= Aa(b)) {
                                        if (b & 256)
                                            return a[a.length - 1][c]
                                    } else {
                                        var e = a.length;
                                        if (d && b & 256 && (d = a[e - 1][c],
                                        null != d))
                                            return d;
                                        b = c + _.Ba(b);
                                        if (b < e)
                                            return a[b]
                                    }
                                }
                                ;
                                _.pc = function(a, b, c) {
                                    const d = a.ma;
                                    let e = d[_.v];
                                    _.Ga(e);
                                    _.eb(d, e, b, c);
                                    return a
                                }
                                ;
                                _.D = function(a, b) {
                                    a = _.oc(a, b);
                                    return null == a || "boolean" === typeof a ? a : "number" === typeof a ? !!a : void 0
                                }
                                ;
                                _.F = function(a, b, c, d=!1) {
                                    b = _.gb(a, b, c, d);
                                    if (null == b)
                                        return b;
                                    a = a.ma;
                                    let e = a[_.v];
                                    if (!(e & 2)) {
                                        const f = _.db(b);
                                        f !== b && (b = f,
                                        _.eb(a, e, c, b, d))
                                    }
                                    return b
                                }
                                ;
                                _.G = function(a, b, c) {
                                    null == c && (c = void 0);
                                    return _.pc(a, b, c)
                                }
                                ;
                                _.H = function(a, b) {
                                    return _.Na(_.oc(a, b))
                                }
                                ;
                                _.I = function(a, b) {
                                    return _.hb(_.D(a, b), !1)
                                }
                                ;
                                _.qc = function(a, b, c=0) {
                                    a = a.ma;
                                    let d = a[_.v];
                                    const e = _.fb(a, d, b);
                                    var f = null == e || "number" === typeof e ? e : "NaN" === e || "Infinity" === e || "-Infinity" === e ? Number(e) : void 0;
                                    null != f && f !== e && _.eb(a, d, b, f);
                                    return _.hb(f, c)
                                }
                                ;
                                _.K = function(a, b) {
                                    return _.hb(_.H(a, b), "")
                                }
                                ;
                                _.L = function(a, b, c) {
                                    if (null != c && "boolean" !== typeof c)
                                        throw Error("q`" + _.tb(c) + "`" + c);
                                    return _.pc(a, b, c)
                                }
                                ;
                                _.N = function(a, b, c) {
                                    return _.pc(a, b, null == c ? c : _.La(c))
                                }
                                ;
                                _.O = function(a, b, c) {
                                    return _.pc(a, b, _.Ma(c))
                                }
                                ;
                                _.P = function(a, b, c) {
                                    return _.pc(a, b, null == c ? c : _.Ka(c))
                                }
                                ;
                                _.Q = class {
                                    constructor(a, b, c) {
                                        this.ma = _.Ta(a, b, c)
                                    }
                                    toJSON() {
                                        if (kc)
                                            var a = lb(this, this.ma, !1);
                                        else
                                            a = Za(this.ma, ab, void 0, void 0, !1, !1),
                                            a = lb(this, a, !0);
                                        return a
                                    }
                                    Ha() {
                                        kc = !0;
                                        try {
                                            return JSON.stringify(this.toJSON(), Va)
                                        } finally {
                                            kc = !1
                                        }
                                    }
                                    Ac() {
                                        return !!((this.ma[_.v] | 0) & 2)
                                    }
                                }
                                ;
                                _.Q.prototype.Sd = _.Oa;
                                _.Q.prototype.toString = function() {
                                    return lb(this, this.ma, !1).toString()
                                }
                                ;
                                _.rc = Symbol();
                                _.sc = Symbol();
                                _.tc = Symbol();
                                _.uc = Symbol();
                                _.vc = Symbol();
                                var wc = class extends _.Q {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                _.xc = class extends _.Q {
                                    constructor() {
                                        super()
                                    }
                                    Bd(a) {
                                        return _.N(this, 3, a)
                                    }
                                }
                                ;
                                var yc = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var zc = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                    Tc(a) {
                                        return _.O(this, 24, a)
                                    }
                                }
                                ;
                                _.Ac = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                _.Bc = function() {
                                    this.Ja = this.Ja;
                                    this.na = this.na
                                }
                                ;
                                _.Bc.prototype.Ja = !1;
                                _.Bc.prototype.isDisposed = function() {
                                    return this.Ja
                                }
                                ;
                                _.Bc.prototype.qa = function() {
                                    this.Ja || (this.Ja = !0,
                                    this.O())
                                }
                                ;
                                _.Bc.prototype.O = function() {
                                    if (this.na)
                                        for (; this.na.length; )
                                            this.na.shift()()
                                }
                                ;
                                var Cc = class extends _.Bc {
                                    constructor() {
                                        var a = window;
                                        super();
                                        this.o = a;
                                        this.i = [];
                                        this.j = {}
                                    }
                                    resolve(a) {
                                        var b = this.o;
                                        a = a.split(".");
                                        for (var c = a.length, d = 0; d < c; ++d)
                                            if (b[a[d]])
                                                b = b[a[d]];
                                            else
                                                return null;
                                        return b instanceof Function ? b : null
                                    }
                                    Xb() {
                                        for (var a = this.i.length, b = this.i, c = [], d = 0; d < a; ++d) {
                                            var e = b[d].i()
                                              , f = this.resolve(e);
                                            if (f && f != this.j[e])
                                                try {
                                                    b[d].Xb(f)
                                                } catch (g) {}
                                            else
                                                c.push(b[d])
                                        }
                                        this.i = c.concat(b.slice(a))
                                    }
                                }
                                ;
                                var Ec = class extends _.Bc {
                                    constructor() {
                                        var a = _.Dc;
                                        super();
                                        this.o = a;
                                        this.A = this.i = null;
                                        this.v = 0;
                                        this.B = {};
                                        this.j = !1;
                                        a = window.navigator.userAgent;
                                        0 <= a.indexOf("MSIE") && 0 <= a.indexOf("Trident") && (a = /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a)) && a[1] && 9 > parseFloat(a[1]) && (this.j = !0)
                                    }
                                    C(a, b) {
                                        this.i = b;
                                        this.A = a;
                                        b.preventDefault ? b.preventDefault() : b.returnValue = !1
                                    }
                                }
                                ;
                                _.Fc = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var Gc = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var Ic;
                                _.Hc = function(a, b) {
                                    if (a.i) {
                                        const c = new wc;
                                        _.O(c, 1, b.message);
                                        _.O(c, 2, b.stack);
                                        _.N(c, 3, b.lineNumber);
                                        _.P(c, 5, 1);
                                        b = new _.xc;
                                        _.G(b, 40, c);
                                        a.i.log(98, b)
                                    }
                                }
                                ;
                                Ic = class {
                                    constructor() {
                                        this.i = null
                                    }
                                    log(a) {
                                        _.Hc(this, a)
                                    }
                                }
                                ;
                                var Lc, Mc, Pc, Rc;
                                _.Jc = class {
                                    constructor(a) {
                                        this.i = a
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.Jc.prototype.xc = !0;
                                _.Jc.prototype.Yb = function() {
                                    return this.i.toString()
                                }
                                ;
                                _.Kc = function(a) {
                                    return a instanceof _.Jc && a.constructor === _.Jc ? a.i : "type_error:SafeUrl"
                                }
                                ;
                                Lc = /^data:(.*);base64,[a-z0-9+\/]+=*$/i;
                                Mc = /^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;
                                _.Oc = function(a) {
                                    if (a instanceof _.Jc)
                                        return a;
                                    a = "object" == typeof a && a.xc ? a.Yb() : String(a);
                                    Mc.test(a) ? a = _.Nc(a) : (a = String(a).replace(/(%0A|%0D)/g, ""),
                                    a = a.match(Lc) ? _.Nc(a) : null);
                                    return a
                                }
                                ;
                                try {
                                    new URL("s://g"),
                                    Pc = !0
                                } catch (a) {
                                    Pc = !1
                                }
                                _.Qc = Pc;
                                Rc = {};
                                _.Nc = function(a) {
                                    return new _.Jc(a,Rc)
                                }
                                ;
                                _.Sc = _.Nc("about:invalid#zClosurez");
                                var Tc, Wc, Vc;
                                _.Uc = function(a) {
                                    let b;
                                    b = window.google && window.google.logUrl ? "" : "https://www.google.com";
                                    b += "/gen_204?use_corp=on&";
                                    b += a.Ha(2040 - b.length);
                                    Tc(_.Oc(b) || _.Sc)
                                }
                                ;
                                Tc = function(a) {
                                    var b = new Image
                                      , c = Vc;
                                    b.onerror = b.onload = b.onabort = function() {
                                        c in Wc && delete Wc[c]
                                    }
                                    ;
                                    Wc[Vc++] = b;
                                    b.src = _.Kc(a)
                                }
                                ;
                                Wc = [];
                                Vc = 0;
                                _.Xc = class {
                                    constructor() {
                                        this.data = {}
                                    }
                                    Ha(a) {
                                        var b = [], c;
                                        for (c in this.data)
                                            b.push(encodeURIComponent(c) + "=" + encodeURIComponent(String(this.data[c])));
                                        return ("atyp=i&zx=" + (new Date).getTime() + "&" + b.join("&")).substr(0, a)
                                    }
                                }
                                ;
                                var Yc = class extends _.Xc {
                                    constructor(a) {
                                        super();
                                        var b = _.F(a, yc, 8) || new yc;
                                        window.google && window.google.kEI && (this.data.ei = window.google.kEI);
                                        this.data.sei = _.x(_.H(a, 10));
                                        this.data.ogf = _.x(_.H(b, 3));
                                        this.data.ogrp = (window.google && window.google.sn ? !/.*hp$/.test(window.google.sn) : _.w(_.D(a, 7))) ? "1" : "";
                                        this.data.ogv = _.x(_.H(b, 6)) + "." + _.x(_.H(b, 7));
                                        this.data.ogd = _.x(_.H(a, 21));
                                        this.data.ogc = _.x(_.H(a, 20));
                                        this.data.ogl = _.x(_.H(a, 5));
                                        this.data.oggv = "quantum:gapiBuildLabel"
                                    }
                                }
                                ;
                                var nb = "constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");
                                var Zc = [1, 2, 3, 4, 5, 6, 9, 10, 11, 13, 14, 28, 29, 30, 34, 35, 37, 38, 39, 40, 42, 43, 48, 49, 50, 51, 52, 53, 62, 500]
                                  , ad = function(a) {
                                    if (!$c) {
                                        $c = {};
                                        for (var b = 0; b < Zc.length; b++)
                                            $c[Zc[b]] = !0
                                    }
                                    return !!$c[a]
                                }
                                  , bd = function(a) {
                                    a = String(a);
                                    return a.replace(".", "%2E").replace(",", "%2C")
                                }
                                  , cd = class extends Yc {
                                    constructor(a, b, c, d, e) {
                                        super(a);
                                        _.ob(this.data, {
                                            oge: c,
                                            ogex: _.x(_.H(a, 9)),
                                            ogp: _.x(_.H(a, 6)),
                                            ogsr: Math.round(1 / (ad(c) ? _.mb(_.qc(b, 3, 1)) : _.mb(_.qc(b, 2, 1E-4)))),
                                            ogus: d
                                        });
                                        if (e) {
                                            "ogw"in e && (this.data.ogw = e.ogw,
                                            delete e.ogw);
                                            "ved"in e && (this.data.ved = e.ved,
                                            delete e.ved);
                                            a = [];
                                            for (var f in e)
                                                0 != a.length && a.push(","),
                                                a.push(bd(f)),
                                                a.push("."),
                                                a.push(bd(e[f]));
                                            e = a.join("");
                                            "" != e && (this.data.ogad = e)
                                        }
                                    }
                                }
                                  , $c = null;
                                var dd = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var hd = class {
                                    constructor() {
                                        var a = ed
                                          , b = fd
                                          , c = gd;
                                        this.i = a;
                                        this.v = b;
                                        this.o = _.mb(_.qc(a, 2, 1E-4), 1E-4);
                                        this.B = _.mb(_.qc(a, 3, 1), 1);
                                        b = Math.random();
                                        this.j = _.w(_.D(a, 1)) && b < this.o;
                                        this.A = _.w(_.D(a, 1)) && b < this.B;
                                        a = 0;
                                        _.w(_.D(c, 1)) && (a |= 1);
                                        _.w(_.D(c, 2)) && (a |= 2);
                                        _.w(_.D(c, 3)) && (a |= 4);
                                        this.C = a
                                    }
                                    log(a, b) {
                                        try {
                                            if (ad(a) ? this.A : this.j) {
                                                const c = new cd(this.v,this.i,a,this.C,b);
                                                _.Uc(c)
                                            }
                                        } catch (c) {}
                                    }
                                }
                                ;
                                var kd;
                                _.id = function(a) {
                                    if (0 < a.j.length) {
                                        var b = void 0 !== a.va
                                          , c = void 0 !== a.i;
                                        if (b || c) {
                                            b = b ? a.o : a.v;
                                            c = a.j;
                                            a.j = [];
                                            try {
                                                _.Fb(c, b, a)
                                            } catch (d) {
                                                console.error(d)
                                            }
                                        }
                                    }
                                }
                                ;
                                _.ld = class {
                                    constructor(a) {
                                        this.va = a;
                                        this.i = void 0;
                                        this.j = []
                                    }
                                    then(a, b, c) {
                                        this.j.push(new kd(a,b,c));
                                        _.id(this)
                                    }
                                    resolve(a) {
                                        if (void 0 !== this.va || void 0 !== this.i)
                                            throw Error("v");
                                        this.va = a;
                                        _.id(this)
                                    }
                                    o(a) {
                                        a.j && a.j.call(a.i, this.va)
                                    }
                                    v(a) {
                                        a.o && a.o.call(a.i, this.i)
                                    }
                                }
                                ;
                                kd = class {
                                    constructor(a, b, c) {
                                        this.j = a;
                                        this.o = b;
                                        this.i = c
                                    }
                                }
                                ;
                                _.md = a=>{
                                    var b = "yc";
                                    if (a.yc && a.hasOwnProperty(b))
                                        return a.yc;
                                    b = new a;
                                    return a.yc = b
                                }
                                ;
                                _.nd = class {
                                    constructor() {
                                        this.v = new _.ld;
                                        this.i = new _.ld;
                                        this.D = new _.ld;
                                        this.B = new _.ld;
                                        this.C = new _.ld;
                                        this.A = new _.ld;
                                        this.o = new _.ld;
                                        this.j = new _.ld;
                                        this.H = new _.ld
                                    }
                                    K() {
                                        return this.v
                                    }
                                    M() {
                                        return this.i
                                    }
                                    N() {
                                        return this.D
                                    }
                                    L() {
                                        return this.B
                                    }
                                    Ja() {
                                        return this.C
                                    }
                                    na() {
                                        return this.A
                                    }
                                    J() {
                                        return this.o
                                    }
                                    G() {
                                        return this.j
                                    }
                                    static i() {
                                        return _.md(_.nd)
                                    }
                                }
                                ;
                                var sd;
                                _.pd = function() {
                                    return _.F(_.od, zc, 1)
                                }
                                ;
                                _.qd = function() {
                                    return _.F(_.od, _.Ac, 5)
                                }
                                ;
                                sd = class extends _.Q {
                                    constructor() {
                                        super(rd)
                                    }
                                }
                                ;
                                var rd;
                                window.gbar_ && window.gbar_.CONFIG ? rd = window.gbar_.CONFIG[0] || {} : rd = [];
                                _.od = new sd;
                                var fd, gd, ed;
                                _.F(_.od, Gc, 3) || new Gc;
                                _.pd() || new zc;
                                _.Dc = new Ic;
                                fd = _.pd() || new zc;
                                gd = _.qd() || new _.Ac;
                                ed = _.F(_.od, dd, 4) || new dd;
                                new hd;
                                _.A("gbar_._DumpException", function(a) {
                                    _.Dc ? _.Dc.log(a) : console.error(a)
                                });
                                _.td = new Ec;
                                var vd;
                                _.wd = function(a, b) {
                                    var c = _.ud.i();
                                    if (a in c.i) {
                                        if (c.i[a] != b)
                                            throw new vd;
                                    } else {
                                        c.i[a] = b;
                                        if (b = c.j[a])
                                            for (let d = 0, e = b.length; d < e; d++)
                                                b[d].i(c.i, a);
                                        delete c.j[a]
                                    }
                                }
                                ;
                                _.ud = class {
                                    constructor() {
                                        this.i = {};
                                        this.j = {}
                                    }
                                    static i() {
                                        return _.md(_.ud)
                                    }
                                }
                                ;
                                _.xd = class extends _.aa {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                vd = class extends _.xd {
                                }
                                ;
                                _.A("gbar.A", _.ld);
                                _.ld.prototype.aa = _.ld.prototype.then;
                                _.A("gbar.B", _.nd);
                                _.nd.prototype.ba = _.nd.prototype.M;
                                _.nd.prototype.bb = _.nd.prototype.N;
                                _.nd.prototype.bd = _.nd.prototype.Ja;
                                _.nd.prototype.bf = _.nd.prototype.K;
                                _.nd.prototype.bg = _.nd.prototype.L;
                                _.nd.prototype.bh = _.nd.prototype.na;
                                _.nd.prototype.bj = _.nd.prototype.J;
                                _.nd.prototype.bk = _.nd.prototype.G;
                                _.A("gbar.a", _.nd.i());
                                window.gbar && window.gbar.ap && window.gbar.ap(window.gbar.a);
                                var yd = new Cc;
                                _.wd("api", yd);
                                var zd = _.qd() || new _.Ac;
                                window.__PVT = _.x(_.H(zd, 8));
                                _.wd("eq", _.td);
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.Ad = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var Bd = class extends _.Q {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                var Cd = class extends _.Bc {
                                    constructor() {
                                        super();
                                        this.j = [];
                                        this.i = []
                                    }
                                    o(a, b) {
                                        this.j.push({
                                            features: a,
                                            options: b
                                        })
                                    }
                                    init(a, b, c) {
                                        window.gapi = {};
                                        var d = window.___jsl = {};
                                        d.h = _.x(_.H(a, 1));
                                        null != _.D(a, 12) && (d.dpo = _.w(_.I(a, 12)));
                                        d.ms = _.x(_.H(a, 2));
                                        d.m = _.x(_.H(a, 3));
                                        d.l = [];
                                        _.K(b, 1) && (a = _.H(b, 3)) && this.i.push(a);
                                        _.K(c, 1) && (c = _.H(c, 2)) && this.i.push(c);
                                        _.A("gapi.load", (0,
                                        _.y)(this.o, this));
                                        return this
                                    }
                                }
                                ;
                                var Dd = _.F(_.od, _.Fc, 14);
                                if (Dd) {
                                    var Ed = _.F(_.od, _.Ad, 9) || new _.Ad
                                      , Fd = new Bd
                                      , Gd = new Cd;
                                    Gd.init(Dd, Ed, Fd);
                                    _.wd("gs", Gd)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;
                    });
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_3', '\x3cg-snackbar jsname\x3d\x22Fd92vb\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 data-dismiss\x3d\x22\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x220ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4G8IBg\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3eKh\xf4ng thi\u1ebft l\u1eadp \u0111\u01b0\u1ee3c l\u1ef1a ch\u1ecdn \u01b0u ti\xean c\u1ee7a b\u1ea1n. H\xe3y th\u1eed l\u1ea1i.\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_5', '\x3cdiv jscontroller\x3d\x22w4UyN\x22 class\x3d\x22fLciMb\x22 data-po\x3d\x22360\x22 aria-label\x3d\x22C\xe0i \u0111\u1eb7t\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22rcuQ6b:npT2md;HfCvm;mouseenter:eGiyHb;focus:eGiyHb;focusin:eGiyHb;mouseleave:LfDNce;focusout:LfDNce\x22 data-ved\x3d\x220ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q6psICBk\x22\x3e\x3cspan class\x3d\x22z1asCe E9hVAb\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M13.85 22.25h-3.7c-.74 0-1.36-.54-1.45-1.27l-.27-1.89c-.27-.14-.53-.29-.79-.46l-1.8.72c-.7.26-1.47-.03-1.81-.65L2.2 15.53c-.35-.66-.2-1.44.36-1.88l1.53-1.19c-.01-.15-.02-.3-.02-.46 0-.15.01-.31.02-.46l-1.52-1.19c-.59-.45-.74-1.26-.37-1.88l1.85-3.19c.34-.62 1.11-.9 1.79-.63l1.81.73c.26-.17.52-.32.78-.46l.27-1.91c.09-.7.71-1.25 1.44-1.25h3.7c.74 0 1.36.54 1.45 1.27l.27 1.89c.27.14.53.29.79.46l1.8-.72c.71-.26 1.48.03 1.82.65l1.84 3.18c.36.66.2 1.44-.36 1.88l-1.52 1.19c.01.15.02.3.02.46s-.01.31-.02.46l1.52 1.19c.56.45.72 1.23.37 1.86l-1.86 3.22c-.34.62-1.11.9-1.8.63l-1.8-.72c-.26.17-.52.32-.78.46l-.27 1.91c-.1.68-.72 1.22-1.46 1.22zm-3.23-2h2.76l.37-2.55.53-.22c.44-.18.88-.44 1.34-.78l.45-.34 2.38.96 1.38-2.4-2.03-1.58.07-.56c.03-.26.06-.51.06-.78s-.03-.53-.06-.78l-.07-.56 2.03-1.58-1.39-2.4-2.39.96-.45-.35c-.42-.32-.87-.58-1.33-.77l-.52-.22-.37-2.55h-2.76l-.37 2.55-.53.21c-.44.19-.88.44-1.34.79l-.45.33-2.38-.95-1.39 2.39 2.03 1.58-.07.56a7 7 0 0 0-.06.79c0 .26.02.53.06.78l.07.56-2.03 1.58 1.38 2.4 2.39-.96.45.35c.43.33.86.58 1.33.77l.53.22.38 2.55z\x22\x3e\x3c/path\x3e\x3ccircle cx\x3d\x2212\x22 cy\x3d\x2212\x22 r\x3d\x223.5\x22\x3e\x3c/circle\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv jsname\x3d\x22suEOdc\x22 class\x3d\x22ZOyvub\x22\x3eC\xe0i \u0111\u1eb7t nhanh\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_7', '\x3cspan class\x3d\x22gb\x22 style\x3d\x22display:none\x22\x3e\x3c/span\x3e\x3cdiv class\x3d\x22gb_Ka gb_f gb_bb gb_j gb_Jc\x22 id\x3d\x22gb\x22 style\x3d\x22background-color:rgba(32,33,36,1)\x22\x3e\x3cdiv class\x3d\x22gb_vd gb_9a gb_kd\x22 data-ogsr-up\x3d\x22\x22\x3e\x3cdiv class\x3d\x22gb_Pd\x22\x3e\x3cdiv class\x3d\x22gb_1c\x22\x3e\x3cdiv class\x3d\x22gb_l gb_v gb_D\x22 data-ogsr-fb\x3d\x22true\x22 data-ogsr-alt\x3d\x22\x22 id\x3d\x22gbwa\x22\x3e\x3cdiv class\x3d\x22gb_g\x22\x3e\x3ca class\x3d\x22gb_d\x22 aria-label\x3d\x22C\xe1c \u1ee9ng d\u1ee5ng c\u1ee7a Google\x22 href\x3d\x22https://www.google.com.vn/intl/vi/about/products?tab\x3dwh\x22 aria-expanded\x3d\x22false\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3e\x3csvg class\x3d\x22gb_i\x22 focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z\x22\x3e\x3c/path\x3e\x3cimage src\x3d\x22https://ssl.gstatic.com/gb/images/bar/al-icon.png\x22 alt\x3d\x22\x22 height\x3d\x2224\x22 width\x3d\x2224\x22 style\x3d\x22border:none;display:none \\9\x22\x3e\x3c/image\x3e\x3c/svg\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22gb_b gb_v gb_Xf gb_D\x22\x3e\x3cdiv class\x3d\x22gb_g gb_8a gb_Xf gb_D\x22\x3e\x3ca class\x3d\x22gb_d gb_Aa gb_D\x22 aria-label\x3d\x22T\xe0i kho\u1ea3n Google: Ngoc Khoa  \x26#10;(ngockhoannk@gmail.com)\x22 href\x3d\x22https://accounts.google.com/SignOutOptions?hl\x3dvi\x26amp;continue\x3dhttps://www.google.com/search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw%253A1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26udm%3D%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\x26amp;ec\x3dGBRAAQ\x22 tabindex\x3d\x220\x22 role\x3d\x22button\x22\x3e\x3cimg class\x3d\x22gb_n gbii\x22 src\x3d\x22https://lh3.googleusercontent.com/ogw/ANLem4bqSzgprxZAeWDQlSNJGFzOA1Tq-5SNdY5lBH4nOw\x3ds32-c-mo\x22 srcset\x3d\x22https://lh3.googleusercontent.com/ogw/ANLem4bqSzgprxZAeWDQlSNJGFzOA1Tq-5SNdY5lBH4nOw\x3ds32-c-mo 1x, https://lh3.googleusercontent.com/ogw/ANLem4bqSzgprxZAeWDQlSNJGFzOA1Tq-5SNdY5lBH4nOw\x3ds64-c-mo 2x \x22 alt\x3d\x22\x22 aria-hidden\x3d\x22true\x22 data-noaft\x3d\x22\x22\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_18', '\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c zriOQb UU8UAb yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;tbm\x3dnws\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnms\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_AUoAHoECAEQCg\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M12 11h6v2h-6v-2zm-6 6h12v-2H6v2zm0-4h4V7H6v6zm16-7.22v12.44c0 1.54-1.34 2.78-3 2.78H5c-1.64 0-3-1.25-3-2.78V5.78C2 4.26 3.36 3 5 3h14c1.64 0 3 1.25 3 2.78zM19.99 12V5.78c0-.42-.46-.78-1-.78H5c-.54 0-1 .36-1 .78v12.44c0 .42.46.78 1 .78h14c.54 0 1-.36 1-.78V12zM12 9h6V7h-6v2\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eTin t\u1ee9c\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22https://www.google.com/travel/flights?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;tbm\x3dflm\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnms\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://www.google.com/travel/flights%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26tbm%3Dflm%26sxsrf%3DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411%26source%3Dlnms\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QiaAMKAF6BAgBEAs\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M12.98 12.89l-4.03 4.03.42 2.95L8.24 21l-1.87-3.37L3 15.76l1.12-1.12 2.95.42 4.03-4.03L3 6.77l1.5-1.5 10.04 2.32 4.2-4.2a1.32 1.32 0 0 1 1.87 0c.52.52.52 1.36 0 1.87l-4.2 4.2 2.32 10.04-1.5 1.5-4.25-8.11\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eChuy\u1ebfn bay\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22https://www.google.com/finance?sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q_AUoAnoECAEQDA\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M6 15.5l-3 2.94V10h3v5.5zm5-1.84l-1.57-1.34L8 13.64V6h3v7.66zM16 12l-3 3V2h3v10zm2.81-.19L17 10h5v5l-1.79-1.79L13 20.36l-3.47-3.02L5.75 21H3l6.47-6.34L13 17.64l5.81-5.83\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eTa\u0300i chi\u0301nh\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_22', '\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QtvsKegQIARAR\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/setprefs?sig\x3d0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\x26amp;safeui\x3don\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/setprefs%3Fsig%3D0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%253D%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526sca_esv%253D595895911%2526sxsrf%253DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%2526ei%253DUbGXZZzCLtrt-Ab08IXABg%2526ved%253D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%2526uact%253D5%2526oq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526gs_lp%253DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%2526sclient%253Dgws-wiz-serp%26safeui%3Don\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q3roKegQIARAT\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eL\u1ecdc b\u1ecf k\u1ebft qu\u1ea3 ph\u1ea3n c\u1ea3m\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 data-nohref\x3d\x221\x22 href\x3d\x22#\x22 aria-label\x3d\x22L\xe0m m\u1edd h\xecnh \u1ea3nh ph\u1ea3n c\u1ea3m, \u0111\xe3 ch\u1ecdn\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d%23\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q3boKegQIARAU\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22wWjvRd z1asCe rH6l6\x22 style\x3d\x22height:16px;line-height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eL\xe0m m\u1edd h\xecnh \u1ea3nh ph\u1ea3n c\u1ea3m\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/setprefs?sig\x3d0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\x26amp;safeui\x3doff\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/setprefs%3Fsig%3D0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%253D%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526sca_esv%253D595895911%2526sxsrf%253DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%2526ei%253DUbGXZZzCLtrt-Ab08IXABg%2526ved%253D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%2526uact%253D5%2526oq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526gs_lp%253DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%2526sclient%253Dgws-wiz-serp%26safeui%3Doff\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q37oKegQIARAV\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eT\u1eaft\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 style\x3d\x22margin:0\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe LGiluc\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22separator\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r8\x22\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/safesearch?hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q3fwIegQIARAW\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cdiv class\x3d\x22z4R3Z yb2zA\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eT\xecm hi\u1ec3u th\xeam v\u1ec1 t\xednh n\u0103ng T\xecm ki\u1ebfm an to\xe0n\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tn_1', '\x3cdiv class\x3d\x22LkcePc\x22\x3e\x3c/div\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;Bmu0r0\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd Yg3U7e\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eM\u1ecdi ng\xf4n ng\u1eef\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eM\u1ecdi ng\xf4n ng\u1eef\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dlr:lang_1vi\x26amp;lr\x3dlang_vi\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBEB0\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3eT\xecm nh\u1eefng trang Ti\u1ebfng Vi\u1ec7t\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;Bmu0r0\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eM\u1ecdi l\xfac\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eM\u1ecdi l\xfac\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:h\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECI\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Gi\u1edd qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:d\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECM\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e 24 gi\u1edd qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:w\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECQ\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Tu\u1ea7n qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:m\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECU\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Th\xe1ng qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:y\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECY\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e N\u0103m qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 jscontroller\x3d\x22VD4Qme\x22 data-m\x3d\x22false\x22\x3e\x3cspan role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22EEGHee\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBECc\x22\x3ePh\u1ea1m vi t\xf9y ch\u1ec9nh...\x3c/span\x3e\x3cdiv class\x3d\x22n5Ug4b\x22 style\x3d\x22display:none\x22\x3e\x3cdiv class\x3d\x22vOvh1b\x22 jsaction\x3d\x22xp3IKd\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22J6UZg\x22 aria-modal\x3d\x22true\x22 role\x3d\x22dialog\x22\x3e\x3cdiv class\x3d\x22Jy9Ore\x22 role\x3d\x22heading\x22\x3ePh\u1ea1m vi ng\xe0y t\xf9y ch\u1ec9nh\x3c/div\x3e\x3clabel class\x3d\x22Qtsmnf tmDYm\x22 for\x3d\x22OouJcb\x22\x3eT\u1eeb\x3c/label\x3e\x3clabel class\x3d\x22Qtsmnf iWBKNe\x22 for\x3d\x22rzG2be\x22\x3eT\u1edbi\x3c/label\x3e\x3cdiv class\x3d\x22Gwgzqd\x22 aria-label\x3d\x22\u0110\xf3ng\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22xp3IKd\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22NwEGxd\x22\x3e\x3cdiv class\x3d\x22qomYCd\x22\x3e\x3c/div\x3e\x3cform action\x3d\x22/search\x22 class\x3d\x22T3kYXe\x22 id\x3d\x22T3kYXe\x22 method\x3d\x22get\x22\x3e\x3cinput name\x3d\x22q\x22 value\x3d\x22code m\u1eabu\x22 type\x3d\x22hidden\x22\x3e\x3cinput name\x3d\x22sca_esv\x22 value\x3d\x22595895911\x22 type\x3d\x22hidden\x22\x3e\x3cinput name\x3d\x22sxsrf\x22 value\x3d\x22AM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x22 type\x3d\x22hidden\x22\x3e\x3cinput name\x3d\x22source\x22 type\x3d\x22hidden\x22 value\x3d\x22lnt\x22\x3e\x3cinput value\x3d\x22cdr:1,cd_min:x,cd_max:x\x22 id\x3d\x22HjtPBb\x22 name\x3d\x22tbs\x22 type\x3d\x22hidden\x22\x3e\x3cinput value\x3d\x22\x22 name\x3d\x22tbm\x22 type\x3d\x22hidden\x22\x3e\x3cinput class\x3d\x22OouJcb\x22 type\x3d\x22text\x22 value\x3d\x22\x22 autocomplete\x3d\x22off\x22 id\x3d\x22OouJcb\x22 jsaction\x3d\x22focus:daRB0b\x22\x3e\x3cinput class\x3d\x22rzG2be\x22 type\x3d\x22text\x22 value\x3d\x22\x22 autocomplete\x3d\x22off\x22 id\x3d\x22rzG2be\x22 jsaction\x3d\x22focus:daRB0b\x22\x3e\x3cg-button class\x3d\x22Ru1Ao BwGU8e fE5Rge\x22 jsaction\x3d\x22hNEEAb\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3eT\xecm\x3c/g-button\x3e\x3cinput type\x3d\x22submit\x22 jsaction\x3d\x22zbvklb\x22 style\x3d\x22display:none\x22\x3e\x3c/form\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;Bmu0r0\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eT\xe2\u0301t ca\u0309 k\u1ebft qu\u1ea3\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eT\xe2\u0301t ca\u0309 k\u1ebft qu\u1ea3\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;Bmu0r4\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;source\x3dlnt\x26amp;tbs\x3dli:1\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpwV6BAgBEC0\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3eNguy\xean v\u0103n\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('spic_1', '\x3cdiv jsname\x3d\x22TItCJc\x22 class\x3d\x22CbAZb\x22 id\x3d\x22elPddd\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22mLt3mc\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QzpwIegQIBhAC\x22\x3e\x3cdiv class\x3d\x22cQ2awd\x22\x3e\x3cimg class\x3d\x22bsfygf\x22 src\x3d\x22https://fonts.gstatic.com/s/i/productlogos/googleg/v6/24px.svg\x22 alt\x3d\x22Google\x22\x3e\x3ch1 class\x3d\x22S8wJ3\x22\x3eC\xe0i \u0111\u1eb7t t\xecm ki\u1ebfm\x3c/h1\x3e\x3cspan class\x3d\x22bepeF z1asCe wuXmqc\x22 aria-label\x3d\x22Close\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22UVNdjb\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qy9QJegQIBhAD\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22https://myactivity.google.com/product/search?utm_source\x3dgoogle\x26amp;utm_campaign\x3dquick_settings\x26amp;hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://myactivity.google.com/product/search%3Futm_source%3Dgoogle%26utm_campaign%3Dquick_settings%26hl%3Dvi\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q7JsIegQIBhAE\x22\x3e\x3cspan class\x3d\x22z1asCe dAmgBb\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M4 4v2.01C5.83 3.58 8.73 2 12.01 2 17.53 2 22 6.48 22 12s-4.47 10-9.99 10C6.48 22 2 17.52 2 12h2c0 4.42 3.58 8 8 8s8-3.58 8-8-3.58-8-8-8C9.04 4 6.47 5.61 5.09 8H8v2H2V4h2z\x22\x3e\x3c/path\x3e\x3cpath d\x3d\x22M13 12V6h-2v7l4.97 3.49 1.26-1.55z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv class\x3d\x22uXoAyd\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eNh\u1eadt k\xfd t\xecm ki\u1ebfm\x3c/span\x3e\x3cspan class\x3d\x22kQEH5b\x22\x3e\x3cspan data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QoZYJegQIBhAF\x22\x3e\u0110ang l\u01b0u\x3c/span\x3e\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/safesearch?prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q8JsIegQIBhAG\x22\x3e\x3cspan class\x3d\x22z1asCe\x22\x3e\x3csvg height\x3d\x2224\x22 viewBox\x3d\x220 -960 960 960\x22 width\x3d\x2224\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22\x3e\x3cpath d\x3d\x22m644-428-58-58q9-47-27-88t-93-32l-58-58q17-8 34.5-12t37.5-4q75 0 127.5 52.5T660-500q0 20-4 37.5T644-428Zm128 126-58-56q38-29 67.5-63.5T832-500q-50-101-143.5-160.5T480-720q-29 0-57 4t-55 12l-62-62q41-17 84-25.5t90-8.5q151 0 269 83.5T920-500q-23 59-60.5 109.5T772-302Zm20 246L624-222q-35 11-70.5 16.5T480-200q-151 0-269-83.5T40-500q21-53 53-98.5t73-81.5L56-792l56-56 736 736-56 56ZM222-624q-29 26-53 57t-41 67q50 101 143.5 160.5T480-280q20 0 39-2.5t39-5.5l-36-38q-11 3-21 4.5t-21 1.5q-75 0-127.5-52.5T300-500q0-11 1.5-21t4.5-21l-84-82Zm319 93Zm-151 75Z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv class\x3d\x22uXoAyd\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eT\xecm ki\u1ebfm an to\xe0n\x3c/span\x3e\x3cspan class\x3d\x22kQEH5b\x22\x3eT\xednh n\u0103ng l\xe0m m\u1edd \u0111ang b\u1eadt\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/preferences?lang\x3d1\x26amp;hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411#languages\x22 style\x3d\x22display:flex\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/preferences%3Flang%3D1%26hl%3Dvi%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526sca_esv%253D595895911%2526sxsrf%253DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411%23languages\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q8ZsIegQIBhAH\x22\x3e\x3cspan class\x3d\x22z1asCe Rxk5mb\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zm6.93 6h-2.95a15.65 15.65 0 0 0-1.38-3.56A8.03 8.03 0 0 1 18.92 8zM12 4.04c.83 1.2 1.48 2.53 1.91 3.96h-3.82c.43-1.43 1.08-2.76 1.91-3.96zM4.26 14C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2s.06 1.34.14 2H4.26zm.82 2h2.95c.32 1.25.78 2.45 1.38 3.56A7.987 7.987 0 0 1 5.08 16zm2.95-8H5.08a7.987 7.987 0 0 1 4.33-3.56A15.65 15.65 0 0 0 8.03 8zM12 19.96c-.83-1.2-1.48-2.53-1.91-3.96h3.82c-.43 1.43-1.08 2.76-1.91 3.96zM14.34 14H9.66c-.09-.66-.16-1.32-.16-2s.07-1.35.16-2h4.68c.09.65.16 1.32.16 2s-.07 1.34-.16 2zm.25 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95a8.03 8.03 0 0 1-4.33 3.56zM16.36 14c.08-.66.14-1.32.14-2s-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2h-3.38z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv class\x3d\x22uXoAyd\x22\x3e\x3cdiv class\x3d\x22ZI7elf UCGAnb\x22\x3eNg\xf4n ng\u1eef\x3cspan style\x3d\x22font-size:12px\x22\x3e (Language)\x3c/span\x3e\x3c/div\x3e\x3cspan class\x3d\x22kQEH5b\x22\x3eTi\u1ebfng Vi\u1ec7t\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/setprefs?hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKmC53gon5oVJNpTz76dGEIMF40Lhw:1704440145768%26ei%3DUbGXZZzCLtrt-Ab08IXABg%26ved%3D0ahUKEwjcrrer3sWDAxXaNt4KHXR4AWgQ4dUDCBA%26uact%3D5%26oq%3Dcode%2Bm%25E1%25BA%25ABu%26gs_lp%3DEgxnd3Mtd2l6LXNlcnAiCmNvZGUgbeG6q3UyBRAAGIAEMggQABiABBjLATIFEAAYgAQyCBAAGIAEGMsBMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESOMQUMcEWNkPcAZ4AZABApgBbqABjwiqAQM4LjO4AQPIAQD4AQHCAgoQABhHGNYEGLADwgIEECMYJ8ICBBAAGAPCAgUQLhiABMICDhAAGIAEGIoFGLEDGIMBwgIHEAAYgAQYCsICEBAAGIAEGIoFGAoYsQMYgwHCAgUQIRigAcICBRAhGJ8F4gMEGAAgQYgGAZAGCA%26sclient%3Dgws-wiz-serp%26pccc%3D1\x26amp;sig\x3d0_2LUSfnbzJ64QyQ5Pjtx8TFgOtGs%3D\x26amp;cs\x3d1\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QqsEHegQIBhAI\x26amp;ictx\x3d1\x22\x3e\x3cspan class\x3d\x22z1asCe tSAV7\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 enable-background\x3d\x22new 0 0 24 24\x22 height\x3d\x2224\x22 viewBox\x3d\x220 0 24 24\x22 width\x3d\x2224\x22\x3e\x3crect fill\x3d\x22none\x22 height\x3d\x2224\x22 width\x3d\x2224\x22\x3e\x3c/rect\x3e\x3cpath d\x3d\x22M9.37,5.51C9.19,6.15,9.1,6.82,9.1,7.5c0,4.08,3.32,7.4,7.4,7.4c0.68,0,1.35-0.09,1.99-0.27C17.45,17.19,14.93,19,12,19 c-3.86,0-7-3.14-7-7C5,9.07,6.81,6.55,9.37,5.51z M12,3c-4.97,0-9,4.03-9,9s4.03,9,9,9s9-4.03,9-9c0-0.46-0.04-0.92-0.1-1.36 c-0.98,1.37-2.58,2.26-4.4,2.26c-2.98,0-5.4-2.42-5.4-5.4c0-1.81,0.89-3.42,2.26-4.4C12.92,3.04,12.46,3,12,3L12,3z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv class\x3d\x22uXoAyd\x22\x3e\x3cspan class\x3d\x22ZI7elf UCGAnb\x22\x3eGiao di\u1ec7n t\u1ed1i\x3c/span\x3e\x3cspan class\x3d\x22kQEH5b\x22\x3eTheo gi\xe1 tr\u1ecb m\u1eb7c \u0111\u1ecbnh c\u1ee7a thi\u1ebft b\u1ecb\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3ca class\x3d\x22tGS0Nc\x22 href\x3d\x22/preferences?hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x22 tabindex\x3d\x220\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/preferences%3Fhl%3Dvi%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bm%2525E1%2525BA%2525ABu%2526sca_esv%253D595895911%2526sxsrf%253DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q65sIegQIBhAJ\x22\x3eCh\u1ebf \u0111\u1ed9 c\xe0i \u0111\u1eb7t kh\xe1c\x3cspan class\x3d\x22z1asCe GNeCNe\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3cdiv class\x3d\x22m0uvVb fgc1P\x22\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3cdiv jsname\x3d\x22QTykS\x22 class\x3d\x22S4xgid\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22VsgDoc\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q85sIegQIBhAK\x22\x3e\x3cspan style\x3d\x22color:#9aa0a6\x22 class\x3d\x22z1asCe dC6Tmc\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H5.17l-.59.59-.58.58V4h16v12z\x22\x3e\x3c/path\x3e\x3cpath d\x3d\x22M11 12h2v2h-2zm0-6h2v4h-2z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eG\u01b0\u0309i ph\u1ea3n h\u1ed3i\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/advanced_search?q\x3dcode+m%E1%BA%ABu\x26amp;sca_esv\x3d595895911\x26amp;sxsrf\x3dAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411\x26amp;hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/advanced_search%3Fq%3Dcode%2Bm%25E1%25BA%25ABu%26sca_esv%3D595895911%26sxsrf%3DAM9HkKkzN6EQEayspiqLhAw3DfCurJNr4A:1704440154411%26hl%3Dvi\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q7psIegQIBhAL\x22\x3e\x3cspan class\x3d\x22z1asCe\x22\x3e\x3csvg height\x3d\x2224\x22 viewBox\x3d\x220 96 960 960\x22 width\x3d\x2224\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22\x3e\x3cpath d\x3d\x22M336 960q-69.72 0-118.86-49.14T168 792V408q-30 0-51-21.187-21-21.186-21-50.937v-72.125Q96 234 117.15 213q21.15-21 50.85-21h336q29.7 0 50.85 21.187Q576 234.373 576 264.124v72.125Q576 366 554.85 387 533.7 408 504 408v152q-33 20-58.5 48.5T405 672h-69v-72h96v-48h-96v-72h96v-72H240v384q0 40 28 68t68 28q20.25 0 37.125-7.5T403 860q8 17 17 33t21 30q-22 17-48.308 27T336 960Zm0-168v-72h54q-4 18-5 36t1 36h-50ZM168 336h336v-72H168v72Zm0 0v-72 72Zm455.775 528Q664 864 692 836.225q28-27.774 28-68Q720 728 692.225 700q-27.774-28-68-28Q584 672 556 699.775q-28 27.774-28 68Q528 808 555.775 836q27.774 28 68 28ZM813 1008l-98-98q-20 13-43.5 19.5t-47.733 6.5q-69.903 0-118.835-49Q456 838 456 768t49-119q49-49 119-49t119 48.932q49 48.932 49 118.835 0 24.233-6.5 47.733Q779 839 766 859l98 98-51 51Z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eT.ki\u1ebfm n\xe2ng cao\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22kzt0Nc\x22\x3e\x3ca href\x3d\x22https://support.google.com/websearch/?p\x3ddsrp_search_hc\x26amp;hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://support.google.com/websearch/%3Fp%3Ddsrp_search_hc%26hl%3Dvi\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q8psIegQIBhAM\x22\x3eTr\u1ee3 gi\xfap\x3c/a\x3e\x26nbsp;\u2022\x26nbsp;\x3ca href\x3d\x22https://policies.google.com/privacy?hl\x3dvi\x26amp;fg\x3d1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://policies.google.com/privacy%3Fhl%3Dvi%26fg%3D1\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QxZEKegQIBhAN\x22\x3eQuy\u1ec1n ri\xeang t\u01b0\x3c/a\x3e\x26nbsp;\u2022\x26nbsp;\x3ca href\x3d\x22https://policies.google.com/terms?hl\x3dvi\x26amp;fg\x3d1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://policies.google.com/terms%3Fhl%3Dvi%26fg%3D1\x26amp;ved\x3d2ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qu58KegQIBhAO\x22\x3e\u0110i\u1ec1u kho\u1ea3n\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_9', '    \x3cdiv jsname\x3d\x22rSAM5d\x22\x3e \x3cdiv style\x3d\x22opacity:0\x22 id\x3d\x22arc-stev\x22 data-jiis\x3d\x22up\x22 data-async-type\x3d\x22arc\x22 data-async-context-required\x3d\x22arc_id,q\x22 class\x3d\x22yp\x22 data-async-rclass\x3d\x22search\x22\x3e\x3c/div\x3e \x3c/div\x3e \x3cdiv jsname\x3d\x22UefMMd\x22 class\x3d\x22wEjo2 s6JM6d\x22 style\x3d\x22display:none\x22\x3e  \x3cdiv class\x3d\x22rskU3c\x22 aria-valuetext\x3d\x22\u0110ang ta\u0309i...\x22 role\x3d\x22progressbar\x22\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22bOiwif\x22\x3e\x3c/div\x3e\x3c/div\x3e \x3c/div\x3e \x3cdiv jsname\x3d\x22Ei53Y\x22 style\x3d\x22display:none\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QsMoFegQIBxAA\x22\x3e \x3c/div\x3e   ');
                }
                )();
                (function() {
                    window.jsl.dh('spch', '\x3cbutton class\x3d\x22close-button\x22 id\x3d\x22spchx\x22 aria-label\x3d\x22\u0111\xf3ng\x22\x3e\x26times;\x3c/button\x3e\x3cdiv class\x3d\x22spchc\x22 id\x3d\x22spchc\x22\x3e\x3cdiv class\x3d\x22inner-container\x22\x3e\x3cdiv class\x3d\x22button-container\x22\x3e\x3cspan class\x3d\x22r8s4j\x22 id\x3d\x22spchl\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22LgbsSe\x22 id\x3d\x22spchb\x22\x3e\x3cdiv class\x3d\x22microphone\x22\x3e\x3cspan class\x3d\x22receiver\x22\x3e\x3c/span\x3e\x3cdiv class\x3d\x22wrapper\x22\x3e\x3cspan class\x3d\x22stem\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22shell\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22text-container\x22\x3e\x3cspan class\x3d\x22spcht\x22 style\x3d\x22color:#9aa0a6\x22 id\x3d\x22spchi\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22spcht\x22 style\x3d\x22color:#bdc1c6\x22 id\x3d\x22spchf\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22google-logo\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22permission-bar\x22\x3e\x3cdiv class\x3d\x22permission-bar-gradient\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('fbar', '\x3cdiv jscontroller\x3d\x22a6Sgfb\x22 jsmodel\x3d\x22J9Q59e\x22 jsdata\x3d\x22YzXGMb;_;Bmu0rc\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22fbar b2hzT\x22\x3e\x3cdiv class\x3d\x22b0KoTc B4GxFc\x22\x3e\x3cspan class\x3d\x22Q8LRLc\x22\x3eVi\u1ec7t Nam\x3c/span\x3e\x3cdiv class\x3d\x22fbar smiUbb\x22 id\x3d\x22swml\x22\x3e\x3cdiv jscontroller\x3d\x22qcH9Lc\x22 jsdata\x3d\x22z6bOeb;_;Bmu0rk\x22 jsaction\x3d\x22oEnJg:CEnhyd;gJk92:b6DXXd\x22\x3e\x3cdiv class\x3d\x22rwA8ec HDOrGf GNm3Qb\x22 style\x3d\x22white-space:normal\x22\x3e\x3ca jsname\x3d\x22gXWYVe\x22 href\x3d\x22#\x22 style\x3d\x22white-space:normal\x22 data-biw\x3d\x221364\x22 jsaction\x3d\x22click:HTIlC\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QuZ0HegQIAhAC\x22\x3e\x3cdiv class\x3d\x22GNm3Qb\x22\x3e\x3cspan class\x3d\x22EYqSq unknown_loc\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22dfB0uf\x22\x3eB\u1ebfn Ngh\xe9, Qu\u1eadn 1, Th\xe0nh ph\u1ed1 H\u1ed3 Ch\xed Minh\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22GNm3Qb\x22\x3e\x3cspan id\x3d\x22VdZal\x22\x3e\x26nbsp;-\x26nbsp;\x3c/span\x3e\x3cspan class\x3d\x22KwU3F\x22\x3e\x3cspan\x3eD\u1ef1a tr\xean v\u1ecb tr\xed c\u1ee7a b\u1ea1n (N\u01a1i l\xe0m vi\u1ec7c)\x3c/span\x3e\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3cspan id\x3d\x22tsuid_11\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3cspan id\x3d\x22RYW0de\x22\x3e\x26nbsp;-\x26nbsp;\x3c/span\x3e\x3cupdate-location class\x3d\x22xSQxL HDOrGf\x22 jscontroller\x3d\x22KgxeNb\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22click:T1dibd;gfszqc:b4F0De;\x22 jsdata\x3d\x22ITZAN;_;Bmu0rw\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QpLkCegQIAhAE\x22\x3eC\u1eadp nh\u1eadt v\u1ecb tr\xed\x3cspan id\x3d\x22tsuid_14\x22\x3e\x3c/span\x3e\x3cspan id\x3d\x22tsuid_20\x22\x3e\x3c/span\x3e\x3c/update-location\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jscontroller\x3d\x22EfPGub\x22 class\x3d\x22RLQCVb\x22\x3e\x3cspan class\x3d\x22B4GxFc wHYlTd z8gr9e\x22\x3eXem tu\u1ef3 ch\u1ecdn kh\xe1c trong ph\u1ea7n \x3ca jsname\x3d\x22hgPHmf\x22 class\x3d\x22GS5rRd\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22em3SNd\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Qw6sKegQIAhAK\x22\x3eC\xe0i \u0111\u1eb7t nhanh (\x3cspan class\x3d\x22SLbK8e z1asCe E9hVAb\x22 style\x3d\x22height:16px;line-height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M13.85 22.25h-3.7c-.74 0-1.36-.54-1.45-1.27l-.27-1.89c-.27-.14-.53-.29-.79-.46l-1.8.72c-.7.26-1.47-.03-1.81-.65L2.2 15.53c-.35-.66-.2-1.44.36-1.88l1.53-1.19c-.01-.15-.02-.3-.02-.46 0-.15.01-.31.02-.46l-1.52-1.19c-.59-.45-.74-1.26-.37-1.88l1.85-3.19c.34-.62 1.11-.9 1.79-.63l1.81.73c.26-.17.52-.32.78-.46l.27-1.91c.09-.7.71-1.25 1.44-1.25h3.7c.74 0 1.36.54 1.45 1.27l.27 1.89c.27.14.53.29.79.46l1.8-.72c.71-.26 1.48.03 1.82.65l1.84 3.18c.36.66.2 1.44-.36 1.88l-1.52 1.19c.01.15.02.3.02.46s-.01.31-.02.46l1.52 1.19c.56.45.72 1.23.37 1.86l-1.86 3.22c-.34.62-1.11.9-1.8.63l-1.8-.72c-.26.17-.52.32-.78.46l-.27 1.91c-.1.68-.72 1.22-1.46 1.22zm-3.23-2h2.76l.37-2.55.53-.22c.44-.18.88-.44 1.34-.78l.45-.34 2.38.96 1.38-2.4-2.03-1.58.07-.56c.03-.26.06-.51.06-.78s-.03-.53-.06-.78l-.07-.56 2.03-1.58-1.39-2.4-2.39.96-.45-.35c-.42-.32-.87-.58-1.33-.77l-.52-.22-.37-2.55h-2.76l-.37 2.55-.53.21c-.44.19-.88.44-1.34.79l-.45.33-2.38-.95-1.39 2.39 2.03 1.58-.07.56a7 7 0 0 0-.06.79c0 .26.02.53.06.78l.07.56-2.03 1.58 1.38 2.4 2.39-.96.45.35c.43.33.86.58 1.33.77l.53.22.38 2.55z\x22\x3e\x3c/path\x3e\x3ccircle cx\x3d\x2212\x22 cy\x3d\x2212\x22 r\x3d\x223.5\x22\x3e\x3c/circle\x3e\x3c/svg\x3e\x3c/span\x3e)\x3c/a\x3e\x3c/span\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_11', '\x3cg-dialog jsname\x3d\x22BDbGbf\x22 jscontroller\x3d\x22VEbNoe\x22 data-id\x3d\x22_WrGXZcTbGIHc1e8P9Y2o8A8_13\x22 jsaction\x3d\x22jxvro:Imgh9b\x22 jsdata\x3d\x22gctHtc;_;Bmu0ro\x22 jsshadow\x3d\x22\x22\x3e\x3cdiv jsname\x3d\x22XKSfm\x22 id\x3d\x22_WrGXZcTbGIHc1e8P9Y2o8A8_13\x22 jsaction\x3d\x22dBhwS:TvD9Pc;mLt3mc\x22\x3e\x3c/div\x3e\x3c/g-dialog\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_14', '\x3clocation-snackbar-with-learn-more jsname\x3d\x22nw18gf\x22 jscontroller\x3d\x22khkNpe\x22 jsaction\x3d\x22sFrcje:No7Jhf\x22\x3e\x3cspan id\x3d\x22tsuid_16\x22\x3e\x3c/span\x3e\x3c/location-snackbar-with-learn-more\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_20', '\x3cg-snackbar jsname\x3d\x22M8d6me\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4G96BAgCEAk\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3e\u0110ang c\u1eadp nh\u1eadt v\u1ecb tr\xed...\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_13', '\x3cdiv jsname\x3d\x22bF1uUb\x22 class\x3d\x22kJFf0c KUf18\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22mcPPZ yMNJR nP0TDe xg7rAe\x22 jsaction\x3d\x22trigger.dBhwS\x22\x3e\x3cdiv class\x3d\x22LjfRsf\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22focus:sT2f3e\x22\x3e\x3c/div\x3e\x3cspan jsslot\x3d\x22\x22 jsaction\x3d\x22mLt3mc\x22\x3e\x3cdiv class\x3d\x22qk7LXc TUOsUe Fb1AKc OosGzb\x22 aria-labelledby\x3d\x22lQ3q8c\x22 role\x3d\x22dialog\x22\x3e\x3cdiv jsname\x3d\x22C8RmQc\x22 id\x3d\x22C8RmQc\x22 data-jiis\x3d\x22up\x22 data-async-type\x3d\x22lbsc\x22 class\x3d\x22yp\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/span\x3e\x3cdiv class\x3d\x22LjfRsf\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22focus:tuePCd\x22\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_16', '\x3cg-snackbar jsname\x3d\x22Ng57nc\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 data-dismiss\x3d\x22\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4Q4G96BAgCEAU\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3eKh\xf4ng th\u1ec3 c\u1eadp nh\u1eadt v\u1ecb tr\xed c\u1ee7a b\u1ea1n\x3c/span\x3e\x3cg-snackbar-action class\x3d\x22sHFNYd zJUuqf AB4Wff Z7swgb\x22 jsname\x3d\x22zrfavf\x22 jscontroller\x3d\x22xRxDld\x22 jsaction\x3d\x22GtUzrb\x22 data-ved\x3d\x222ahUKEwjE8Mav3sWDAxUBbvUHHfUGCv4QhbkIegQIAhAH\x22\x3e\x3cg-flat-button class\x3d\x22U8shWc r2fjmd hObAcc gTewb VDgVie hpZDWd fSXIc\x22 style\x3d\x22color:#7baaf7\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3e\x3cspan class\x3d\x22Omzzbd\x22\x3eTi\u0300m hi\xea\u0309u th\xeam\x3c/span\x3e\x3c/g-flat-button\x3e\x3c/g-snackbar-action\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_WrGXZcTbGIHc1e8P9Y2o8A8_24', '\x3cdiv\x3e\x3cdiv\x3e\x3cdiv class\x3d\x22gb_ed\x22\x3eC\xe1c \u1ee9ng d\u1ee5ng c\u1ee7a Google\x3c/div\x3e\x3cdiv class\x3d\x22gb_q\x22\x3e\x3cdiv class\x3d\x22gb_zc\x22\x3e\x3cdiv\x3eT\xe0i kho\u1ea3n Google\x3c/div\x3e\x3cdiv class\x3d\x22gb_zb\x22\x3eNgoc Khoa\x3c/div\x3e\x3cdiv\x3engockhoannk@gmail.com\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e', function() {
                        window.gbar && gbar.up && gbar.up.tp && gbar.up.tp();
                        this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                _.Hd = function(a, b, c) {
                                    if (!a.j)
                                        if (c instanceof Array)
                                            for (var d of c)
                                                _.Hd(a, b, d);
                                        else {
                                            d = (0,
                                            _.y)(a.C, a, b);
                                            const e = a.v + c;
                                            a.v++;
                                            b.dataset.eqid = e;
                                            a.B[e] = d;
                                            b && b.addEventListener ? b.addEventListener(c, d, !1) : b && b.attachEvent ? b.attachEvent("on" + c, d) : a.o.log(Error("s`" + b))
                                        }
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.Id = function() {
                                    if (!_.q.addEventListener || !Object.defineProperty)
                                        return !1;
                                    var a = !1
                                      , b = Object.defineProperty({}, "passive", {
                                        get: function() {
                                            a = !0
                                        }
                                    });
                                    try {
                                        const c = ()=>{}
                                        ;
                                        _.q.addEventListener("test", c, b);
                                        _.q.removeEventListener("test", c, b)
                                    } catch (c) {}
                                    return a
                                }();
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var Jd = document.querySelector(".gb_l .gb_d")
                                  , Kd = document.querySelector("#gb.gb_Rc");
                                Jd && !Kd && _.Hd(_.td, Jd, "click");
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.Ah = function(a) {
                                    const b = [];
                                    let c = 0;
                                    for (const d in a)
                                        b[c++] = a[d];
                                    return b
                                }
                                ;
                                _.Bh = function(a) {
                                    if (a.o)
                                        return a.o;
                                    for (const b in a.i)
                                        if (a.i[b].ta() && a.i[b].B())
                                            return a.i[b];
                                    return null
                                }
                                ;
                                _.Ch = function(a, b) {
                                    a.i[b.K()] = b
                                }
                                ;
                                var Dh = new class extends _.Bc {
                                    constructor() {
                                        var a = _.Dc;
                                        super();
                                        this.B = a;
                                        this.o = null;
                                        this.j = {};
                                        this.C = {};
                                        this.i = {};
                                        this.v = null
                                    }
                                    A(a) {
                                        this.i[a] && (_.Bh(this) && _.Bh(this).K() == a || this.i[a].P(!0))
                                    }
                                    Ya(a) {
                                        this.v = a;
                                        for (const b in this.i)
                                            this.i[b].ta() && this.i[b].Ya(a)
                                    }
                                    uc(a) {
                                        return a in this.i ? this.i[a] : null
                                    }
                                }
                                ;
                                _.wd("dd", Dh);
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.kj = function(a, b) {
                                    return _.L(a, 36, b)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var lj = document.querySelector(".gb_b .gb_d")
                                  , mj = document.querySelector("#gb.gb_Rc");
                                lj && !mj && _.Hd(_.td, lj, "click");
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                var Md, Pd;
                                _.Ld = function(a) {
                                    const b = a.length;
                                    if (0 < b) {
                                        const c = Array(b);
                                        for (let d = 0; d < b; d++)
                                            c[d] = a[d];
                                        return c
                                    }
                                    return []
                                }
                                ;
                                Md = function(a) {
                                    return a
                                }
                                ;
                                _.Nd = function(a) {
                                    var b = null
                                      , c = _.q.trustedTypes;
                                    if (!c || !c.createPolicy)
                                        return b;
                                    try {
                                        b = c.createPolicy(a, {
                                            createHTML: Md,
                                            createScript: Md,
                                            createScriptURL: Md
                                        })
                                    } catch (d) {
                                        _.q.console && _.q.console.error(d.message)
                                    }
                                    return b
                                }
                                ;
                                _.Od = function(a, b) {
                                    return 0 == a.lastIndexOf(b, 0)
                                }
                                ;
                                _.Qd = function() {
                                    void 0 === Pd && (Pd = _.Nd("ogb-qtm#html"));
                                    return Pd
                                }
                                ;
                                try {
                                    (new self.OffscreenCanvas(0,0)).getContext("2d")
                                } catch (a) {}
                                ;_.Rd = {};
                                _.Sd = class {
                                    constructor(a) {
                                        this.i = a;
                                        this.xc = !0
                                    }
                                    Yb() {
                                        return this.i
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.Td = new _.Sd("",_.Rd);
                                _.Ud = RegExp("^[-+,.\"'%_!#/ a-zA-Z0-9\\[\\]]+$");
                                _.Vd = RegExp("\\b(url\\([ \t\n]*)('[ -&(-\\[\\]-~]*'|\"[ !#-\\[\\]-~]*\"|[!#-&*-\\[\\]-~]*)([ \t\n]*\\))", "g");
                                _.Wd = RegExp("\\b(calc|cubic-bezier|fit-content|hsl|hsla|linear-gradient|matrix|minmax|radial-gradient|repeat|rgb|rgba|(rotate|scale|translate)(X|Y|Z|3d)?|steps|var)\\([-+*/0-9a-zA-Z.%#\\[\\], ]+\\)", "g");
                                var Xd;
                                Xd = {};
                                _.Zd = function(a) {
                                    return a instanceof _.Yd && a.constructor === _.Yd ? a.i : "type_error:SafeHtml"
                                }
                                ;
                                _.$d = function(a) {
                                    const b = _.Qd();
                                    a = b ? b.createHTML(a) : a;
                                    return new _.Yd(a,Xd)
                                }
                                ;
                                _.Yd = class {
                                    constructor(a) {
                                        this.i = a;
                                        this.xc = !0
                                    }
                                    Yb() {
                                        return this.i.toString()
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.ae = new _.Yd(_.q.trustedTypes && _.q.trustedTypes.emptyHTML || "",Xd);
                                _.be = _.$d("<br>");
                                var de;
                                _.ce = function(a) {
                                    let b = !1, c;
                                    return function() {
                                        b || (c = a(),
                                        b = !0);
                                        return c
                                    }
                                }(function() {
                                    var a = document.createElement("div")
                                      , b = document.createElement("div");
                                    b.appendChild(document.createElement("div"));
                                    a.appendChild(b);
                                    b = a.firstChild.firstChild;
                                    a.innerHTML = _.Zd(_.ae);
                                    return !b.parentElement
                                });
                                de = /^[\w+/_-]+[=]{0,2}$/;
                                _.ee = function(a) {
                                    a = (a || _.q).document;
                                    return a.querySelector ? (a = a.querySelector('style[nonce],link[rel="stylesheet"][nonce]')) && (a = a.nonce || a.getAttribute("nonce")) && de.test(a) ? a : "" : ""
                                }
                                ;
                                _.fe = function(a, b) {
                                    this.width = a;
                                    this.height = b
                                }
                                ;
                                _.m = _.fe.prototype;
                                _.m.aspectRatio = function() {
                                    return this.width / this.height
                                }
                                ;
                                _.m.Hb = function() {
                                    return !(this.width * this.height)
                                }
                                ;
                                _.m.ceil = function() {
                                    this.width = Math.ceil(this.width);
                                    this.height = Math.ceil(this.height);
                                    return this
                                }
                                ;
                                _.m.floor = function() {
                                    this.width = Math.floor(this.width);
                                    this.height = Math.floor(this.height);
                                    return this
                                }
                                ;
                                _.m.round = function() {
                                    this.width = Math.round(this.width);
                                    this.height = Math.round(this.height);
                                    return this
                                }
                                ;
                                _.R = function(a, b) {
                                    var c = b || document;
                                    if (c.getElementsByClassName)
                                        a = c.getElementsByClassName(a)[0];
                                    else {
                                        c = document;
                                        var d = b || c;
                                        a = d.querySelectorAll && d.querySelector && a ? d.querySelector(a ? "." + a : "") : _.ge(c, a, b)[0] || null
                                    }
                                    return a || null
                                }
                                ;
                                _.ge = function(a, b, c) {
                                    var d;
                                    a = c || a;
                                    if (a.querySelectorAll && a.querySelector && b)
                                        return a.querySelectorAll(b ? "." + b : "");
                                    if (b && a.getElementsByClassName) {
                                        var e = a.getElementsByClassName(b);
                                        return e
                                    }
                                    e = a.getElementsByTagName("*");
                                    if (b) {
                                        var f = {};
                                        for (c = d = 0; a = e[c]; c++) {
                                            var g = a.className;
                                            "function" == typeof g.split && _.sa(g.split(/\s+/), b) && (f[d++] = a)
                                        }
                                        f.length = d;
                                        return f
                                    }
                                    return e
                                }
                                ;
                                _.ie = function(a) {
                                    return _.he(document, a)
                                }
                                ;
                                _.he = function(a, b) {
                                    b = String(b);
                                    "application/xhtml+xml" === a.contentType && (b = b.toLowerCase());
                                    return a.createElement(b)
                                }
                                ;
                                _.je = function(a) {
                                    for (var b; b = a.firstChild; )
                                        a.removeChild(b)
                                }
                                ;
                                _.ke = function(a) {
                                    return 9 == a.nodeType ? a : a.ownerDocument || a.document
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var Ge, Ie;
                                _.Be = function(a) {
                                    if (null == a)
                                        return a;
                                    if ("string" === typeof a) {
                                        if (!a)
                                            return;
                                        a = +a
                                    }
                                    if ("number" === typeof a)
                                        return Number.isFinite(a) ? a | 0 : void 0
                                }
                                ;
                                _.Ce = function(a, b) {
                                    var c = Array.prototype.slice.call(arguments, 1);
                                    return function() {
                                        var d = c.slice();
                                        d.push.apply(d, arguments);
                                        return a.apply(this, d)
                                    }
                                }
                                ;
                                _.De = function(a, b) {
                                    return _.Be(_.oc(a, b))
                                }
                                ;
                                _.T = function(a, b) {
                                    a = _.oc(a, b);
                                    return null == a ? a : Number.isFinite(a) ? a | 0 : void 0
                                }
                                ;
                                _.Ee = function(a, b) {
                                    if (void 0 !== a.va || void 0 !== a.i)
                                        throw Error("v");
                                    a.i = b;
                                    _.id(a)
                                }
                                ;
                                _.Fe = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                Ge = class extends _.xd {
                                }
                                ;
                                _.He = function(a, b) {
                                    if (b in a.i)
                                        return a.i[b];
                                    throw new Ge;
                                }
                                ;
                                Ie = 0;
                                _.Je = function(a) {
                                    return Object.prototype.hasOwnProperty.call(a, _.vb) && a[_.vb] || (a[_.vb] = ++Ie)
                                }
                                ;
                                _.Ke = function(a) {
                                    return _.He(_.ud.i(), a)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                /*

 SPDX-License-Identifier: Apache-2.0
*/
                                var rj = function(a) {
                                    return new _.qj(b=>b.substr(0, a.length + 1).toLowerCase() === a + ":")
                                };
                                _.qj = class {
                                    constructor(a) {
                                        this.Wg = a
                                    }
                                }
                                ;
                                _.sj = [rj("data"), rj("http"), rj("https"), rj("mailto"), rj("ftp"), new _.qj(a=>/^[^:]*([/?#]|$)/.test(a))];
                                _.tj = "function" === typeof URL;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var uj;
                                uj = {};
                                _.vj = class {
                                    constructor(a) {
                                        this.i = a
                                    }
                                    toString() {
                                        return this.i + ""
                                    }
                                }
                                ;
                                _.vj.prototype.xc = !0;
                                _.vj.prototype.Yb = function() {
                                    return this.i.toString()
                                }
                                ;
                                _.wj = function(a) {
                                    return a instanceof _.vj && a.constructor === _.vj ? a.i : "type_error:TrustedResourceUrl"
                                }
                                ;
                                _.xj = function(a) {
                                    const b = _.Qd();
                                    a = b ? b.createScriptURL(a) : a;
                                    return new _.vj(a,uj)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.yj = function(a) {
                                    var b;
                                    let c;
                                    const d = null == (c = (b = (a.ownerDocument && a.ownerDocument.defaultView || window).document).querySelector) ? void 0 : c.call(b, "script[nonce]");
                                    (b = d ? d.nonce || d.getAttribute("nonce") || "" : "") && a.setAttribute("nonce", b)
                                }
                                ;
                                _.zj = function(a) {
                                    if (!a)
                                        return null;
                                    a = _.H(a, 4);
                                    var b;
                                    null === a || void 0 === a ? b = null : b = _.xj(a);
                                    return b
                                }
                                ;
                                _.Aj = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                _.Bj = function(a, b) {
                                    return (b || document).getElementsByTagName(String(a))
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var Dj = function(a, b, c) {
                                    a < b ? Cj(a + 1, b) : _.Dc.log(Error("W`" + a + "`" + b), {
                                        url: c
                                    })
                                }
                                  , Cj = function(a, b) {
                                    if (Ej) {
                                        const c = _.ie("SCRIPT");
                                        c.async = !0;
                                        c.type = "text/javascript";
                                        c.charset = "UTF-8";
                                        c.src = _.wj(Ej);
                                        _.yj(c);
                                        c.onerror = _.Ce(Dj, a, b, c.src);
                                        _.Bj("HEAD")[0].appendChild(c)
                                    }
                                }
                                  , Fj = class extends _.Q {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var Gj = _.F(_.od, Fj, 17) || new Fj, Hj, Ej = (Hj = _.F(Gj, _.Aj, 1)) ? _.zj(Hj) : null, Ij, Jj = (Ij = _.F(Gj, _.Aj, 2)) ? _.zj(Ij) : null, Kj = function() {
                                    Cj(1, 2);
                                    if (Jj) {
                                        const b = _.ie("LINK");
                                        b.setAttribute("type", "text/css");
                                        b.rel = "stylesheet";
                                        b.href = _.wj(Jj).toString();
                                        var a = _.ee(b.ownerDocument && b.ownerDocument.defaultView);
                                        a && b.setAttribute("nonce", a);
                                        (a = _.ee()) && b.setAttribute("nonce", a);
                                        _.Bj("HEAD")[0].appendChild(b)
                                    }
                                };
                                (function() {
                                    const a = _.pd();
                                    if (_.D(a, 18))
                                        Kj();
                                    else {
                                        const b = _.De(a, 19) || 0;
                                        window.addEventListener("load", ()=>{
                                            window.setTimeout(Kj, b)
                                        }
                                        )
                                    }
                                }
                                )();
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;
                    });
                }
                )();
                (function() {
                    google.drty && google.drty(undefined, true);
                }
                )();
            });
        </script>
        <div></div>
        <div jscontroller="EO13pd" class="fp-nh" id="TWfxFb" jsaction="rcuQ6b:npT2md;Egr1he:f0xwYb;vKbCb:dwOkab">
            <div jsname="J7OdWb" data-jiis="up" data-async-type="vpkg" id="QPwIld" class="yp"></div>
        </div>
        <div id="lfootercc">
            <div id="Un6H4"></div>
            <script nonce="x9iHkhRHZETt-9nytNuh5g">
                (function() {
                    var footerDebugCommentsCssId = 'Un6H4';
                    let debugComments = document.getElementById('dc');
                    let footerDebugComments = document.getElementById(footerDebugCommentsCssId);
                    if (debugComments && footerDebugComments) {
                        debugComments.appendChild(footerDebugComments);
                    }
                }
                )();
            </script>
            <script nonce="x9iHkhRHZETt-9nytNuh5g">
                (function() {
                    for (var i in google.iir || {}) {
                        _setImagesSrc([i], google.iir[i]);
                    }
                    google.iir = {};
                }
                )();
                google.jslm = 3;
            </script>
            <script nonce="x9iHkhRHZETt-9nytNuh5g">
                (function() {
                    var xsrfTokens = '{\x22UPgwmc\x22:\x22ALook6x0oCe4j5RLxjJFBw9DT1iEfORiiw:1704440154741\x22}';
                    google.xsrf = JSON.parse(xsrfTokens);
                }
                )();
            </script>
            <div id="reviewDialog" data-async-context="async_id_prefix:" data-jiis="up" data-async-type="reviewDialog" data-async-context-required="async_id_prefix" class="yp"></div>
            <div id="dbg_"></div>
        </div>
    </body>
</html>
# FEWW
saca
