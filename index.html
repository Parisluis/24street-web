const branches = {
  S25: {
    name: "S25 · 25 de Mayo",
    shortName: "25 de Mayo",
    address: "25 de Mayo 817 · Tucumán",
    maps: "https://www.google.com/maps/search/?api=1&query=24+Street+25+de+Mayo+817+Tucuman",
    instagram: "https://www.instagram.com/24street.bnorte/"
  },
  AB: {
    name: "AB · Abasto",
    shortName: "Abasto",
    address: "Miguel Lillo 365 · Tucumán",
    maps: "https://www.google.com/maps/search/?api=1&query=24+Street+Miguel+Lillo+365+Tucuman",
    instagram: "https://www.instagram.com/" // TODO: reemplazar por cuenta oficial exacta
  },
  CE: {
    name: "CE · Centro",
    shortName: "Centro",
    address: "Junín y 24 de Septiembre · Tucumán",
    maps: "https://www.google.com/maps/search/?api=1&query=24+Street+Junin+y+24+de+Septiembre+Tucuman",
    instagram: "https://www.instagram.com/" // TODO: reemplazar por cuenta oficial exacta
  },
  FL: {
    name: "FL · Flip",
    shortName: "Flip",
    address: "Av. Aconquija · Yerba Buena",
    maps: "https://www.google.com/maps/search/?api=1&query=24+Street+Av+Aconquija+Yerba+Buena",
    instagram: "https://www.instagram.com/" // TODO: confirmar estado y cuenta oficial
  }
};

const params = new URLSearchParams(window.location.search);
let activeCode = branches[params.get("s")] ? params.get("s") : "S25";

const chip = document.getElementById("branchChip");
const chipText = document.getElementById("branchChipText");
const address = document.getElementById("branchAddress");
const mapsLink = document.getElementById("mapsLink");
const instagramLink = document.getElementById("instagramLink");
const dialog = document.getElementById("branchDialog");
const branchList = document.getElementById("branchList");

function renderBranches() {
  branchList.innerHTML = "";
  Object.entries(branches).forEach(([code, branch]) => {
    const button = document.createElement("button");
    button.type = "button";
    button.className = `branch-option ${code === activeCode ? "active" : ""}`;
    button.innerHTML = `
      <span class="branch-code">${code}</span>
      <span><strong>${branch.shortName}</strong><span>${branch.address}</span></span>
      <span>↗</span>
    `;
    button.addEventListener("click", () => {
      setBranch(code);
      dialog.close();
    });
    branchList.appendChild(button);
  });
}

function setBranch(code) {
  activeCode = code;
  const branch = branches[code];
  chipText.textContent = branch.name;
  address.textContent = branch.address;
  mapsLink.href = branch.maps;
  instagramLink.href = branch.instagram;

  const nextUrl = new URL(window.location.href);
  nextUrl.searchParams.set("s", code);
  history.replaceState({}, "", nextUrl);
  renderBranches();
}

chip.addEventListener("click", () => {
  renderBranches();
  dialog.showModal();
});

// Movimiento sutil de las tarjetas en escritorio.
document.querySelectorAll(".action-card").forEach((card) => {
  card.addEventListener("pointermove", (event) => {
    if (window.matchMedia("(max-width: 820px)").matches) return;
    const rect = card.getBoundingClientRect();
    const x = (event.clientX - rect.left) / rect.width - 0.5;
    const y = (event.clientY - rect.top) / rect.height - 0.5;
    card.style.transform = `perspective(700px) rotateX(${y * -4}deg) rotateY(${x * 5}deg) translateY(-4px)`;
  });
  card.addEventListener("pointerleave", () => {
    card.style.transform = "";
  });
});

setBranch(activeCode);
