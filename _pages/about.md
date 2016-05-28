---
layout: inner
title: About
permalink: /about/
---

<div id="regard" class="text-right"></div>

Saya adalah Putri Pamungkassari, kata ibu bapak saya artinya
**“putri terakhir yang cantik”** (sepertinya).

<div class="row">
    <div class="col-sm-10 col-sm-offset-1">
        Menurut Yanotz Petshop, orang yang lahir dibulan Mei itu :
        <ol>
            <li>
                Memiliki pemikiran tajam
            </li>
            <li>
                Pandai mengambil hati orang lain
            </li>
            <li>
                Mencintai literatur dan seni
            </li>
            <li>
                Memiliki imajinasi yang tinggi
            </li>
            <li>
                Senang menunda pekerjaan
            </li>
            <li>
                Agak boros
            </li>
            <li>
                Mudah dipengaruhi
            </li>
            <li>
                Tidak suka basa-basi
            </li>
            <li>
                Tidak senang dipuji
            </li>
        </ol>
    </div>
</div>

Agaknya 9 sifat di atas sudah cukup menggambarkan diri saya.

<div class="visible-xs">
    <table style="font-size: 12px;">
        <tr>
            <td>Facebook</td>
            <td style="padding: 0 8px;">:</td>
            <td>Putri Pamungkassari</td>
        </tr>
        <tr>
            <td>Twitter</td>
            <td style="padding: 0 8px;">:</td>
            <td>@putri_pepee</td>
        </tr>
        <tr>
            <td>Instagram</td>
            <td style="padding: 0 8px;">:</td>
            <td>@putri_pepe</td>
        </tr>
        <tr>
            <td>Email</td>
            <td style="padding: 0 8px;">:</td>
            <td>putri.pamungkassari@gmail.com</td>
        </tr>
    </table>
</div>
<div style="position: relative;" class="hidden-xs">
    <div class="social-buttons">
        <a
            href="https://www.facebook.com/putripepee"
            class="social-button facebook"
            target="_blank"
        >
            <i class="fa fa-facebook"></i>
        </a>
        <a
            href="https://twitter.com/putri_pepee"
            class="social-button twitter"
            target="_blank"
        >
            <i class="fa fa-twitter"></i>
        </a>
        <a
            href="https://twitter.com/putri_pepee"
            class="social-button instagram"
            target="_blank"
        >
            <i class="fa fa-instagram"></i>
        </a>
        <a
            href="https://plus.google.com/115108173932542101935"
            class="social-button google"
            target="_blank"
        >
            <i class="fa fa-google"></i>
        </a>
    </div>
</div>

<script>
    $(function() {
        var index = 0;
        var regards = [
            'Assalamualaikum',
            'السلام عليكم',
            '<i>as-salāmu \'alaykum</i>',
        ];
        function showRegard() {
            $("#regard").html(regards[index]);
            index++;
            if (index >= regards.length) {
                index = 0;
            }
        };
        showRegard();
        setInterval(showRegard, 5000);
    });
</script>
