<?php

namespace nomanjaved;

class About extends Me
{
    public function getBio(): string
    {
        return 'I hold a Bachelor\'s degree in Computer Science with 7 years of experience in web development. 
                I specialize in both front-end technologies like React, Angular, and Vue.js, and back-end frameworks 
                such as PHP and Laravel. I focus on creating high-performance web applications, leading technical projects, 
                and staying updated with the latest technologies to build reliable and cutting-edge solutions.';
    }

    public function getMore(): array
    {
        return [
            'work' => [
                'Full Stack Developer (Team Lead) - Al-Burraq Technologies (2021 – 2025)',
                'PHP Laravel Developer - Baron Tech (2018 – 2021)',
                'Software Engineer - PROGOS TECH (Pvt) Ltd (2016 – 2018)'
            ]
        ];
    }

    public function getCurrentState(): array 
    {
        return [
            'working_on' => [
                'allcalls.io - Allcalls is a remote opportunity in insurance sales with on-demand client leads. Flexible schedule, daily commissions, performance-based promotions, and management opportunities available.',
                'telaeris.com - Telaeris, Inc. is a US-based software company, specializing in handheld and hands-free safety and physical security solutions to enhance access control and occupancy tracking systems.',
                'NopCommerce (suptomer.com) - A comprehensive supply chain management platform tailored for the food and beverage industry. This system connects suppliers and merchants, streamlines ordering, tracks inventory, and improves communication workflows. Built with a focus on centralised dashboards, role-based access, real-time data insights, and seamless supplier collaboration to drive operational efficiency and digital transformation in supply chains. :contentReference[oaicite:0]{index=0}'
            ],
            'learning' => [
                'Advanced Programming Techniques',
                'AI',
                'Python'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Contribute to open source.';
    }
}
