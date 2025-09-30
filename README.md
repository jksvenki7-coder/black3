# black3<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>JKS Group of Business</title>
<style>
body {
  background: #22232c;
  color: #fff;
  font-family: Arial, sans-serif;
  margin: 0; min-height: 100vh;
}
header {
  font-size: 2.2rem;
  font-weight: bold;
  color: #3aaaff;
  padding: 36px 0 10px 0;
  text-align: center;
  user-select: none;
}
.sub-header {
  color: #7fd0f0;
  font-weight: 600;
  font-size: 1.2rem;
  text-align: center;
  margin: 8px 0 42px 0;
  user-select: none;
}
.add-product {
  width: 56vw;
  max-width: 720px;
  margin: 0 auto 48px auto;
  padding: 24px 0;
  border: 2.5px dashed #ffe066;
  border-radius: 12px;
  text-align: center;
  font-weight: 600;
  font-size: 1.15rem;
  color: #ffe066;
  box-shadow: 0 6px 30px #ffe06655;
  user-select: none;
  background: rgba(255,255,255,0.04);
}
.service-grid {
  width: 70vw;
  max-width: 900px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 28px;
  justify-items: center;
  user-select: none;
}
.service-item {
  background-color: #232335;
  border: 2.5px solid #ffe066;
  border-radius: 10px;
  padding: 20px 12px;
  color: #ffe066;
  font-size: 1.18rem;
  font-weight: 600;
  text-align: center;
  box-shadow: 0 0 18px #ffe066aa;
  cursor: pointer;
  transition: all 0.25s ease;
  user-select: none;
  text-decoration: none;
  display: flex;
  align-items: center;
  justify-content: center;
}
.service-item:hover {
  box-shadow: 0 0 38px #ffe066ff;
  background-color: #232342;
  color: #fffbd0;
  transform: scale(1.07);
}
footer {
  text-align: center;
  padding: 30px 4px 12px 4px;
  font-size: 1rem;
  color: #7fd0f0;
  user-select: none;
}
@media (max-width: 980px) {
  .service-grid {
    grid-template-columns: repeat(2, 1fr);
    width: 90vw;
  }
  .add-product {
    width: 82vw;
  }
}
@media (max-width: 600px) {
  .service-grid {
    grid-template-columns: 1fr;
  }
}
</style>
</head>
<body>
<header>JKS Group of Business</header>
<div class="sub-header">&lt; Add (an) Product Display &gt;</div>
<div class="add-product">Add (an) Product Display</div>
<main class="service-grid">
  <a class="service-item" href="ecommerce.html">My E-commerce</a>
  <a class="service-item" href="events.html">My Events & Catering</a>
  <a class="service-item" href="courier.html">My Courier & My Riders</a>
  <a class="service-item" href="job.html">My Job Consultancy & My Services</a>
  <a class="service-item" href="tours.html">My Tours & My Travel</a>
  <a class="service-item" href="realestate.html">Real Estate & Construction</a>
  <a class="service-item" href="investment.html">Investment & Business</a>
  <a class="service-item" href="loans.html">My Loans & My Insurance</a>
  <a class="service-item" href="homeservices.html">Home Services</a>
</main>
<footer>&copy; 2025 JKS Group of Business. All rights reserved.</footer>
</body>
</html>
