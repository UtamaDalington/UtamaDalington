<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Utama Dalington Professional Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .flow-arrow {
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            color: #F4A261;
        }
        .flow-card {
            border: 2px solid #75B9BE;
            transition: all 0.3s ease;
        }
        .flow-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .tier-box {
            border: 2px dashed #2A9D8F;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-bold text-[#2A9D8F] mb-2">UTAMA DALINGTON</h1>
            <h2 class="text-xl md:text-2xl font-semibold text-[#E76F51]">Cloud & DevOps Engineer | DevSecOps | SRE | Cloud Solutions Architect | AWS Certified | Web & App Developer | Digital Marketer</h2>
            <p class="max-w-3xl mx-auto mt-4 text-gray-600">
                A dynamic professional with a passion for building secure, scalable, and resilient systems. I specialize in the full lifecycle of cloud solutions, from architectural design to automated deployment, complemented by expertise in web development and data-driven marketing.
            </p>
        </header>

        <main>
            <section id="toolbox" class="mb-16">
                <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                    <h3 class="text-2xl md:text-3xl font-bold text-center mb-2 text-[#2A9D8F]">Core Technical & Business Competencies</h3>
                    <p class="text-center text-gray-600 mb-8 max-w-2xl mx-auto">My expertise spans across the entire cloud-native and development landscape, as well as key business disciplines.</p>
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                        <div>
                            <h4 class="text-xl font-bold text-center text-[#E76F51] mb-4">Technical Proficiency</h4>
                            <div class="chart-container">
                                <canvas id="techSkillsRadarChart"></canvas>
                            </div>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold text-center text-[#E76F51] mb-4">Digital Marketing & Strategy</h4>
                            <div class="chart-container">
                                <canvas id="marketingSkillsBarChart"></canvas>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="languages" class="mb-16">
                <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                    <h3 class="text-2xl md:text-3xl font-bold text-center mb-8 text-[#2A9D8F]">Proficient Languages & Technologies</h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                        <div><p class="text-xl font-semibold text-[#E76F51]">Python</p><p class="text-gray-600">Scripting, Automation</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">JavaScript</p><p class="text-gray-600">Web Development</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">TypeScript</p><p class="text-gray-600">Web Development</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Go</p><p class="text-gray-600">System Tools, APIs</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Bash/Shell</p><p class="text-gray-600">System Automation</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Node.js</p><p class="text-gray-600">Backend Development</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">React</p><p class="text-gray-600">Frontend Development</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Angular</p><p class="text-gray-600">Frontend Development</p></div>
                    </div>
                </div>
            </section>
            
            <section id="iac" class="mb-16">
                <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                    <h3 class="text-2xl md:text-3xl font-bold text-center mb-8 text-[#2A9D8F]">Infrastructure as Code & Orchestration</h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                        <div><p class="text-xl font-semibold text-[#E76F51]">Terraform</p><p class="text-gray-600">Multi-Cloud IaC</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Kubernetes</p><p class="text-gray-600">Container Orchestration</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">CloudFormation</p><p class="text-gray-600">AWS-native IaC</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Ansible</p><p class="text-gray-600">Configuration Management</p></div>
                    </div>
                </div>
            </section>

            <section id="ci-sec" class="mb-16">
                <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                    <h3 class="text-2xl md:text-3xl font-bold text-center mb-8 text-[#2A9D8F]">Continuous Integration & Security</h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                        <div><p class="text-xl font-semibold text-[#E76F51]">CI/CD</p><p class="text-gray-600">Pipelines (Jenkins, GitHub Actions, GitLab CI)</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Maven</p><p class="text-gray-600">Build Automation</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Nexus</p><p class="text-gray-600">Artifact Repository</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">SonarQube</p><p class="text-gray-600">Code Quality Analysis</p></div>
                    </div>
                </div>
            </section>

            <section id="monitoring" class="mb-16">
                <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                    <h3 class="text-2xl md:text-3xl font-bold text-center mb-8 text-[#2A9D8F]">Monitoring & Observability</h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                        <div><p class="text-xl font-semibold text-[#E76F51]">Prometheus</p><p class="text-gray-600">Metrics Monitoring</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Grafana</p><p class="text-gray-600">Data Visualization</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">ELK Stack</p><p class="text-gray-600">Log Management</p></div>
                        <div><p class="text-xl font-semibold text-[#E76F51]">Splunk</p><p class="text-gray-600">Log Analysis</p></div>
                    </div>
                </div>
            </section>

            <section id="projects" class="mb-16">
                <h3 class="text-2xl md:text-3xl font-bold text-center mb-12 text-[#2A9D8F]">Featured Projects & Architectural Vision</h3>
                <div class="grid grid-cols-1 md:grid-cols-1 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                        <h4 class="text-xl md:text-2xl font-bold text-[#E76F51] mb-4">Architectural Design: 3-Tier Web Application on AWS</h4>
                        <p class="text-gray-600 mb-6">This design focuses on creating a secure, scalable, and highly available foundation. The architecture isolates each layer to enhance security and performance, using a custom VPC with public and private subnets, controlled by security groups and IAM roles for least-privilege access.</p>
                        <div class="p-4 bg-gray-50 rounded-lg">
                            <div class="tier-box p-4 rounded-lg">
                                <p class="font-bold text-center text-[#2A9D8F]">Virtual Private Cloud (VPC)</p>
                                <div class="grid grid-cols-1 lg:grid-cols-3 gap-4 mt-4 text-center">
                                    <div class="bg-[#75B9BE] bg-opacity-20 p-4 rounded-lg">
                                        <p class="font-semibold">🌐 Web Tier (Public Subnet)</p>
                                        <p class="text-sm mt-2">ALB & Auto Scaling Group</p>
                                    </div>
                                    <div class="bg-[#F4A261] bg-opacity-20 p-4 rounded-lg">
                                        <p class="font-semibold">⚙️ App Tier (Private Subnet)</p>
                                        <p class="text-sm mt-2">EC2 Instances & Auto Scaling</p>
                                    </div>
                                    <div class="bg-[#E76F51] bg-opacity-20 p-4 rounded-lg">
                                        <p class="font-semibold">💾 Data Tier (Private Subnet)</p>
                                        <p class="text-sm mt-2">RDS Database Instances</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                        <h4 class="text-xl md:text-2xl font-bold text-[#E76F51] mb-4">Process: DevSecOps Pipeline Integration</h4>
                         <p class="text-gray-600 mb-6">To catch vulnerabilities early, security is embedded directly into the CI/CD pipeline. This "shift-left" approach uses automated tools to scan container images and infrastructure code, providing real-time feedback and preventing insecure code from reaching production.</p>
                        <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">
                            <div class="flow-card p-4 rounded-lg text-center bg-white w-48 h-24 flex items-center justify-center">Code Commit</div>
                            <div class="flow-arrow">➡️</div>
                            <div class="flow-card p-4 rounded-lg text-center bg-white w-48 h-24 flex items-center justify-center">Build & Test</div>
                            <div class="flow-arrow">➡️</div>
                            <div class="flow-card p-4 rounded-lg text-center bg-white w-48 h-24 flex items-center justify-center">🛡️ Security Scan (Trivy, Checkov)</div>
                            <div class="flow-arrow">➡️</div>
                            <div class="flow-card p-4 rounded-lg text-center bg-white w-48 h-24 flex items-center justify-center">Deploy</div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg shadow-md p-6 md:p-8">
                        <h4 class="text-xl md:text-2xl font-bold text-[#E76F51] mb-4">Deployment: Automated Blue/Green Strategy</h4>
                        <p class="text-gray-600 mb-6">This strategy ensures zero-downtime deployments. A new "green" version of the application is deployed alongside the live "blue" version. After testing, traffic is seamlessly switched to the new version, minimizing user impact and providing a rapid rollback path if needed.</p>
                        <div class="flex flex-col md:flex-row items-stretch justify-center space-y-4 md:space-y-0 md:space-x-4">
                            <div class="flex-1 text-center p-4 bg-blue-100 rounded-lg border-2 border-blue-400">
                                <p class="font-bold text-lg">BLUE (Live Env)</p>
                                <p class="mt-2">Receives 100% of traffic</p>
                            </div>
                            <div class="flow-arrow self-center">🔄</div>
                             <div class="flex-1 text-center p-4 bg-green-100 rounded-lg border-2 border-green-400">
                                <p class="font-bold text-lg">GREEN (New Env)</p>
                                <p class="mt-2">Deployed & Tested. Receives 0% of traffic initially.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="credentials" class="mb-16 text-center">
                 <h3 class="text-2xl md:text-3xl font-bold text-center mb-8 text-[#2A9D8F]">Credentials & Affiliations</h3>
                 <p class="text-gray-600 mb-8 max-w-2xl mx-auto">My expertise is validated by key industry certifications and shaped by prestigious leadership programs.</p>
                 <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <p class="text-4xl font-bold text-[#F4A261] mb-2">DevOps Certified</p>
                        <h4 class="text-xl font-semibold mt-4 text-[#2A9D8F]">Certified Professional</h4>
                        <p class="text-gray-600 mt-2">Demonstrates expertise in implementing and managing DevOps practices to streamline development and operations.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <p class="text-4xl font-bold text-[#F4A261] mb-2">YALI Alumnus</p>
                        <h4 class="text-xl font-semibold mt-4 text-[#2A9D8F]">Young African Leaders Initiative</h4>
                        <p class="text-gray-600 mt-2">A program focused on leadership training, public management, and entrepreneurship development.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <p class="text-4xl font-bold text-[#E76F51] mb-2">TEF Alumnus</p>
                        <h4 class="text-xl font-semibold mt-4 text-[#2A9D8F]">Tony Elumelu Foundation</h4>
                        <p class="text-gray-600 mt-2">Recognized for my entrepreneurial drive and dedication to creating business solutions for local challenges.</p>
                    </div>
                 </div>
            </section>

        </main>

        <footer class="text-center border-t pt-8 mt-8">
            <h3 class="text-xl font-bold text-[#2A9D8F] mb-4">Let's Connect</h3>
            <div class="flex justify-center space-x-6">
                <a href="https://www.linkedin.com/in/utama-dalington-5aba48148/" class="text-gray-600 hover:text-[#E76F51] transition">LinkedIn</a>
                <a href="https://x.com/UtamaDalington" class="text-gray-600 hover:text-[#E76F51] transition">Twitter/X</a>
                <a href="https://medium.com/@utamadalington045" class="text-gray-600 hover:text-[#E76F51] transition">Website</a>
            </div>
        </footer>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const wrapLabel = (str, maxWidth) => {
                if (str.length <= maxWidth) {
                    return str;
                }
                const words = str.split(' ');
                let lines = [];
                let currentLine = '';
                words.forEach(word => {
                    if ((currentLine + word).length > maxWidth) {
                        lines.push(currentLine.trim());
                        currentLine = '';
                    }
                    currentLine += word + ' ';
                });
                lines.push(currentLine.trim());
                return lines;
            };
            
            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                } else {
                    return label;
                }
            };

            const techRadarCtx = document.getElementById('techSkillsRadarChart');
            if (techRadarCtx) {
                new Chart(techRadarCtx, {
                    type: 'radar',
                    data: {
                        labels: [
                            'Cloud Platforms', 
                            'Infrastructure as Code', 
                            ['Containerization &', 'Orchestration'], 
                            'CI/CD Pipelines', 
                            ['Monitoring &', 'Observability'], 
                            ['Web & App', 'Development']
                        ],
                        datasets: [{
                            label: 'Proficiency',
                            data: [95, 95, 92, 88, 85, 90],
                            backgroundColor: 'rgba(231, 111, 81, 0.2)',
                            borderColor: 'rgba(231, 111, 81, 1)',
                            borderWidth: 2,
                            pointBackgroundColor: 'rgba(231, 111, 81, 1)',
                            pointBorderColor: '#fff',
                            pointHoverBackgroundColor: '#fff',
                            pointHoverBorderColor: 'rgba(231, 111, 81, 1)'
                        }]
                    },
                    options: {
                        maintainAspectRatio: false,
                        scales: {
                            r: {
                                angleLines: {
                                    color: '#75B9BE'
                                },
                                grid: {
                                    color: '#75B9BE'
                                },
                                pointLabels: {
                                    font: {
                                        size: 14
                                    },
                                    color: '#2A9D8F'
                                },
                                ticks: {
                                    backdropColor: 'rgba(245, 245, 245, 1)',
                                    color: '#E76F51'
                                }
                            }
                        },
                        plugins: {
                            legend: {
                                display: false
                            },
                            tooltip: {
                                callbacks: {
                                    title: tooltipTitleCallback
                                }
                            }
                        }
                    }
                });
            }

            const marketingBarCtx = document.getElementById('marketingSkillsBarChart');
            if (marketingBarCtx) {
                new Chart(marketingBarCtx, {
                    type: 'bar',
                    data: {
                        labels: [
                            ['Digital Marketing', 'Strategy'], 
                            ['Content Creation &', 'Marketing'], 
                            ['Social Media', 'Management'], 
                            ['Data Analytics &', 'Reporting'], 
                            ['SEO & Paid', 'Advertising']
                        ],
                        datasets: [{
                            label: 'Proficiency',
                            data: [85, 75, 80, 90, 70],
                            backgroundColor: [
                                '#75B9BE',
                                '#F4A261',
                                '#E76F51',
                                '#00A6A6',
                                '#2A9D8F'
                            ],
                            borderColor: [
                                '#75B9BE',
                                '#F4A261',
                                '#E76F51',
                                '#00A6A6',
                                '#2A9D8F'
                            ],
                            borderWidth: 1
                        }]
                    },
                    options: {
                        indexAxis: 'y',
                        responsive: true,
                        maintainAspectRatio: false,
                        scales: {
                            x: {
                                beginAtZero: true,
                                max: 100,
                                grid: {
                                    display: false
                                },
                                ticks: {
                                    display: false
                                }
                            },
                            y: {
                                grid: {
                                    color: '#75B9BE'
                                },
                                ticks: {
                                    color: '#2A9D8F'
                                }
                            }
                        },
                        plugins: {
                            legend: {
                                display: false
                            },
                            tooltip: {
                                callbacks: {
                                    title: tooltipTitleCallback
                                }
                            }
                        }
                    }
                });
            }
        });
    </script>
</body>
</html>
