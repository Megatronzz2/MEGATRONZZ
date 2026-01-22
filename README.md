<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Green Valley College | GVC</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">

  <style>
    :root {
      --green: #228B22;
      --navy: #001F3F;
      --gold: #DAA520;
      --white: #ffffff;
    }

    body {
      scroll-behavior: smooth;
      font-family: "Segoe UI", sans-serif;
    }

    /* Navbar */
    .navbar {
      background-color: var(--navy);
    }

    .navbar-brand span {
      font-weight: 700;
      color: var(--white);
      margin-left: 8px;
    }

    .nav-link {
      color: var(--white) !important;
      margin-right: 10px;
    }

    .nav-link:hover {
      color: var(--gold) !important;
    }

    /* Hero */
    .hero {
      background: linear-gradient(
          rgba(0, 31, 63, 0.8),
          rgba(0, 31, 63, 0.8)
        ),
        url("https://images.unsplash.com/photo-1523050854058-8df90110c9f1");
      background-size: cover;
      background-position: center;
      color: white;
      padding: 120px 20px;
      text-align: center;
    }

    .hero h1 span {
      color: var(--gold);
    }

    /* Section Styling */
    section {
      padding: 70px 0;
    }

    .section-title {
      color: var(--navy);
      margin-bottom: 40px;
      font-weight: 700;
    }

    .card {
      border: none;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    }

    /* Buttons */
    .btn-gvc {
      background-color: var(--green);
      color: white;
      border: none;
    }

    .btn-gvc:hover {
      background-color: var(--gold);
      color: var(--navy);
    }

    /* Footer */
    footer {
      background-color: var(--navy);
      color: white;
      padding: 50px 0 20px;
    }

    footer a {
      color: var(--gold);
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    .social-icons i {
      font-size: 22px;
      margin-right: 15px;
      color: white;
    }

    .social-icons i:hover {
      color: var(--gold);
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark fixed-top">
  <div class="container">
    <a class="navbar-brand d-flex align-items-center" href="#">
      <!-- SVG Logo -->
      <svg width="40" height="30" viewBox="0 0 100 60">
        <path d="M10 50 Q50 5 90 50" fill="#228B22"/>
      </svg>
      <span>GVC</span>
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#gvcNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="gvcNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
        <li class="nav-item"><a class="nav-link" href="#departments">Departments</a></li>
        <li class="nav-item"><a class="nav-link" href="#events">Events</a></li>
        <li class="nav-item"><a class="nav-link" href="#notes">Notes</a></li>
        <li class="nav-item"><a class="nav-link" href="#support">Help & Support</a></li>
        <li class="nav-item"><a class="nav-link" href="#complaint">Complaint Box</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero -->
<section class="hero" id="home">
  <div class="container">
    <h1 class="display-5 fw-bold">
      Welcome to <span>Green Valley College</span>
    </h1>
    <p class="lead mt-3">
      Excellence in Education • Innovation • Integrity
    </p>
    <a href="#about" class="btn btn-gvc mt-4 px-4 py-2">
      Learn More
    </a>
  </div>
</section>

<!-- About -->
<section id="about">
  <div class="container">
    <h2 class="section-title text-center">About Us</h2>
    <p class="text-center mx-auto" style="max-width: 800px;">
      Green Valley College is a premier institution committed to academic
      excellence, holistic development, and community engagement. Located in
      Thiruvananthapuram, Kerala, GVC nurtures future leaders through quality
      education and innovation.
    </p>
  </div>
</section>

<!-- Departments -->
<section id="departments" class="bg-light">
  <div class="container">
    <h2 class="section-title text-center">Departments</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h5>Computer Science</h5>
          <p>Modern computing, AI, and software development.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h5>Commerce & Management</h5>
          <p>Business leadership and financial excellence.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-4 text-center">
          <h5>Humanities</h5>
          <p>Social sciences, languages, and cultural studies.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Events -->
<section id="events">
  <div class="container">
    <h2 class="section-title text-center">Events</h2>
    <ul class="list-group list-group-flush mx-auto" style="max-width: 600px;">
      <li class="list-group-item">🎓 Annual Convocation</li>
      <li class="list-group-item">📚 National Seminar Series</li>
      <li class="list-group-item">🏆 Inter-College Sports Meet</li>
    </ul>
  </div>
</section>

<!-- Notes -->
<section id="notes" class="bg-light">
  <div class="container text-center">
    <h2 class="section-title">Notes</h2>
    <p>Students can access and download study materials here.</p>
    <button class="btn btn-gvc">Coming Soon</button>
  </div>
</section>

<!-- Help & Support -->
<section id="support">
  <div class="container text-center">
    <h2 class="section-title">Help & Support</h2>
    <p>Email: support@gvc.edu.in | Phone: +91 471 000 0000</p>
  </div>
</section>

<!-- Complaint Box -->
<section id="complaint" class="bg-light">
  <div class="container">
    <h2 class="section-title text-center">Complaint Box</h2>
    <form class="mx-auto" style="max-width: 500px;">
      <div class="mb-3">
        <input type="text" class="form-control" placeholder="Your Name" required>
      </div>
      <div class="mb-3">
        <textarea class="form-control" rows="4" placeholder="Your Complaint" required></textarea>
      </div>
      <button class="btn btn-gvc w-100">Submit</button>
    </form>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="container">
    <div class="row">
      <div class="col-md-4 mb-3">
        <h5>Green Valley College</h5>
        <p>
          Thiruvananthapuram,<br>
          Kerala, India
        </p>
      </div>

      <div class="col-md-4 mb-3">
        <h5>Quick Links</h5>
        <ul class="list-unstyled">
          <li><a href="#about">About Us</a></li>
          <li><a href="#departments">Departments</a></li>
          <li><a href="#events">Events</a></li>
        </ul>
      </div>

      <div class="col-md-4 mb-3">
        <h5>Connect With Us</h5>
        <div class="social-icons">
          <i class="bi bi-linkedin"></i>
          <i class="bi bi-instagram"></i>
          <i class="bi bi-youtube"></i>
        </div>
      </div>
    </div>

    <hr class="border-light">

    <p class="text-center mb-0">
      © 2026 Green Valley College. All Rights Reserved.
    </p>
  </div>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
